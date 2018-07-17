# DragandSwipeListView

<b>Drag and drop the list item anywhere in the list and Swipe to delete the item</b>

<br>
<img width="500" height="500" src="https://github.com/ThameemAK/DragandSwipeListView/blob/master/app/src/main/res/drawable/drag_swipe.gif" />
<br>

For “drag & drop” and “swipe-to-dismiss” there are many tutorials, libraries, and examples available in Android using RecyclerView.
There is simple way to add this functionality using one class, and it’s already part of the Android Support Library.

<b>ItemTouchHelper</b> - It is subclass of RecyclerView.ItemDecoration. It takes care of everything.

<b>Must override the following callback methods : </b>

  getMovementFlags(RecyclerView, ViewHolder)

  onMove(RecyclerView, ViewHolder, ViewHolder)

  onSwiped(ViewHolder, int)

<b>There is couple of method available to enable & disable  : </b>

  isLongPressDragEnabled()

  isItemViewSwipeEnabled()


