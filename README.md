# double-linked-list
/*  Insert a node in the list in alphabetical order
• Find a node that matches a String
• Traverse the list forwards and print
• Traverse the list backwards and print
• Delete a node from the list
• Delete/destroy the list
*/

public class LinkedListNode
{

    private String data;
    private LinkedListNode next;


    public LinkedListNode(String data)
    {
        this.data = data;
        this.next = null;
    }

    public String getData()
    {
        return data;
    }

    public LinkedListNode getNext()
    {
        return next;
    }

    public void setNext(LinkedListNode n)
    {
        next = n;
    }
}
