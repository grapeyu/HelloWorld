# HelloWorld-And-TestActivity
HelloWorld的创建

![image](https://github.com/grapeyu/HelloWorld/blob/master/images/搜狗截图20190324151312.jpg)
![image](https://github.com/grapeyu/HelloWorld/blob/master/images/搜狗截图20190324151410.jpg)
![image](https://github.com/grapeyu/HelloWorld/blob/master/images/截屏_20190324_151856.jpg)

验证Activity的周期

public class MainActivity extends AppCompatActivity {
    final String TAG="--MainActivity--";
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Log.d(TAG,"--onCreate--");
    }
    @Override
    protected void onStart() {
        super.onStart();
        Log.d(TAG,"--onStart--");
    }
    @Override
    protected void onResume() {
        super.onResume();
        Log.d(TAG,"--onResume--");
    }
    @Override
    protected void onPause() {
        super.onPause();
        Log.d(TAG,"--onPause--");
    }
    @Override
    protected void onStop() {
        super.onStop();
        Log.d(TAG,"--onStop--");
    }
    @Override
    protected void onDestroy() {
        super.onDestroy();
        Log.d(TAG,"--onDestroy--");
    }
    @Override
    protected void onRestart() {
        super.onRestart();
        Log.d(TAG,"--onRestart--");
    }
}


启动Activity生命周期时
![image](https://github.com/grapeyu/HelloWorld-And-TestActivity/blob/master/images/搜狗截图20190325013110.jpg)

关闭Activity生命周期
![image](https://github.com/grapeyu/HelloWorld-And-TestActivity/blob/master/images/搜狗截图20190325012945.jpg)
