# DATA-STRUCTURES-KEYNOTES-AND-IMPLEMENTATIONS
<h2><b>LINKEDLIST<b></h2>
    
   * LinkedList is a linear data structure that do not store data in a contiguous memory locations</p>
   * <p>LinkedList, unlike arrays, can automatically shrink and increase in size</p>
   * <p>The elements in a LinkedList are linked using pointers</p>
   * <p>Basically, it consists of nodes where each node contains a data field and a reference to the next node in the list.</p>
   * <p>The first node is called the :grinning:<I>head</I></p>
   * <p>The last node is called the <I>tail</I></p><br>
***
<h2>OPERATIONS</h2> <h4>(Algorithm/Pseudocode)</h4>
  <b><h3>Sarching or Looking For elements</h3></b>
  
  * <p>Initialize a node pointer, current = head</p>
  * <p>Do following while current is not NULL.</p>
  * <p>current->key is equal to the key being searched return true.</p>
  * <p>current = current->next.</p>
  * <p>Return false 1. </p>

  <b><h3>DELETION</h3></b>
  
  1. <p>If the head node has the given key, make the head node points to the second node and free its memory.</p>
  Pseudocode:
  <p>firstNode = Head</p>
  <p>Head = firstNode->Next</p>
  <p>free firstNode</p>
  
  2. <p><b>Deleting last node: </b>Traverse to Last Node in the List using two pointers namely prevNode and curNode. 
  Once curNode reaches the last Node in the list point Next in prevNode to NULL and free the curNode.</p>
  <p>Pseudocode:</p>
  <p>curNode = head</p>
<p>forever:</p>
<p> if curNode->Next == NULL</p>
 <p>break</p>
 <p>prevNode = curNode</p>
 <p>curNode = curNode->Next</p>
 <p>prevNode->Next = NULL</p>
<p>free curNode</p>
  3. <p>.</p>


