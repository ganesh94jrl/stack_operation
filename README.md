# Stack Operations 

## Overview
This README provides detailed descriptions of the stack operations you can perform. A stack is a linear data structure that follows the Last In First Out (LIFO) principle, meaning the last element added is the first one to be removed. The operations covered include push(), pop(), isEmpty(), isFull(), peek(), count(), change(), and display().

## Stack Operations

### push(item)
Adds an item to the top of the stack.
- *Parameters:* 
  - item: The item to be added to the stack.
- *Returns:* None
- *Description:* This method places the specified item at the top of the stack. If the stack is already full, an appropriate error or exception is raised.

### pop()
Removes and returns the top item from the stack.
- *Parameters:* None
- *Returns:* The item removed from the top of the stack.
- *Description:* This method removes the item at the top of the stack and returns it. If the stack is empty, an appropriate error or exception is raised.

### isEmpty()
Checks if the stack is empty.
- *Parameters:* None
- *Returns:* True if the stack is empty, False otherwise.
- *Description:* This method checks whether the stack contains any items. If there are no items in the stack, it returns True; otherwise, it returns False.

### isFull()
Checks if the stack is full.
- *Parameters:* None
- *Returns:* True if the stack is full, False otherwise.
- *Description:* This method checks whether the stack has reached its maximum capacity. If the stack is full, it returns True; otherwise, it returns False.

### peek()
Returns the top item of the stack without removing it.
- *Parameters:* None
- *Returns:* The top item of the stack.
- *Description:* This method provides a way to look at the item on the top of the stack without removing it. If the stack is empty, an appropriate error or exception is raised.

### count()
Returns the number of items in the stack.
- *Parameters:* None
- *Returns:* The number of items in the stack.
- *Description:* This method returns the total number of items currently present in the stack.

### change(index, item)
Changes the item at the specified index.
- *Parameters:* 
  - index: The index at which the item should be changed.
  - item: The new item to be placed at the specified index.
- *Returns:* None
- *Description:* This method updates the item at the given index with the new item provided. If the index is out of range, an appropriate error or exception is raised.

### display()
Displays all items in the stack.
- *Parameters:* None
- *Returns:* A list of items in the stack.
- *Description:* This method returns a list of all items currently in the stack, providing a way to see the current state of the stack.

## Example Usage
Here's an example of how these stack operations might be used in practice:

1. *Initialize the Stack*
   - Create a stack with a specified size.
2. *Push Items*
   - Add items to the stack using the push() method.
3. *Pop Items*
   - Remove the top item from the stack using the pop() method.
4. *Check if Empty*
   - Use the isEmpty() method to check if the stack is empty.
5. *Check if Full*
   - Use the isFull() method to check if the stack is full.
6. *Peek at the Top Item*
   - Use the peek() method to view the top item without removing it.
7. *Count Items*
   - Use the count() method to get the number of items in the stack.
8. *Change an Item*
   - Use the change() method to update an item at a specific index.
9. *Display the Stack*
   - Use the display() method to view all items in the stack.

This README provides a clear understanding of the stack operations and their purposes. Make sure to handle any potential errors or exceptions, especially when performing operations on an empty or full stack.
