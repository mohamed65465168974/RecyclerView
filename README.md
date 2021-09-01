# RecyclerView  
1- download recyclerview dependency from the design tab for `activity_main.xml`  
2- add recyclerview to the constraint layout and put constraints to it and set width and height to match constraints  
3- set an id to it  
4- find recycler view inside java file  
```java 
public class MainActivity extends AppCompatActivity {
    
    RecyclerView recyclerView;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        
        recyclerView = findViewById(R.id.recyclerView);
        
    }
}
```
5- create recycler adatper to use the recycler view  
displays items inside the recycler view as it creates the rows and maps the items inside the list to those rows  
6- create a view holder class to be a view holder for the views 
```java
public class RecyclerAdapter {
    class ViewHolder extends RecyclerView.ViewHolder{

        public ViewHolder(@NonNull View itemView) {
            super(itemView);
        }
    }
}
```


