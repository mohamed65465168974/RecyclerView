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
