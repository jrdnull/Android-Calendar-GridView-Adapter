Hope its useful to someone, e.g

// gridview xml layout
<GridView
  android:id="@+id/gridview"
	android:layout_width="fill_parent"
	android:layout_height="fill_parent"
	android:numColumns="7"
    	android:verticalSpacing="1dp"
    	android:horizontalSpacing="1dp"
    	android:gravity="center"
    	android:background="#DADADA"
/>


// get date
mCalendar = Calendar.getInstance();
mToday[0] = mCalendar.get(Calendar.DAY_OF_MONTH);
mToday[1] = mCalendar.get(Calendar.MONTH); // zero based
mToday[2] = mCalendar.get(Calendar.YEAR);


// get display metrics
final DisplayMetrics metrics = new DisplayMetrics();
getWindowManager().getDefaultDisplay().getMetrics(metrics);


// set adapter
mGridView = (GridView)findViewById(R.id.gridview);
mGridView.setAdapter(new MonthAdapter(this, mToday[1], mToday[2], metrics);