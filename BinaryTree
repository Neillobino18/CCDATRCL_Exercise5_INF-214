public class BinaryTree {

    public static void main(String[] args) {

        // Create root node A
        Node President = new Node("Neil");
        // Create node B
        Node vicepresident = new Node("Mycko");
        // Create node C
        Node CEO = new Node("Ronn");
        // Create node D
        Node Manager = new Node("Alexander john");
        // Create node E
        Node Supervisor = new Node("John andrei");
        // Create node F
        Node Employee1 = new Node("Mark");
        // Create node G
        Node Employee2 = new Node("JB");

        // Set left and right child of root node A
        President.left = vicepresident;
        President.right = CEO;

        // Set left and right child of node B
        vicepresident.left = Manager;
        vicepresident.right = Supervisor;

        // Set left and right child of node C
        CEO.left = Employee1;
        CEO.right = Employee2;

       

        System.out.print("\nIn order Traversal: ");
        traverseInOrder(President);

        System.out.print("\nPost order Traversal: ");
        traversePostOrder(President);

        System.out.print("\nPre order Traversal: ");
        traversePreOrder(President);

    }

    // Traverse Inorder Method
    static void traverseInOrder(Node node) {
        if (node != null) {
            traverseInOrder(node.left);
            System.out.print(" " + node.data);
            traverseInOrder(node.right);
        }
    }

    // Traverse Postorder method
    static void traversePostOrder(Node node) {
        if (node != null) {
            traversePostOrder(node.left);
            traversePostOrder(node.right);
            System.out.print(" " + node.data);
        }
    }

    // Traverse Preorder method
    static void traversePreOrder(Node node) {
        if (node != null) {
            System.out.print(" " + node.data);
            traversePreOrder(node.left);
            traversePreOrder(node.right);
        }
    }
}
