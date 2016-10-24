# asd

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/container"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context="com.example.mycalculator.MainActivity">
    tools:ignore="MergeRootFrame"
    android:padding="15dp"
    android:layout_gravity="center"
    android:background="#111"
    >

    <Button
        android:id="@+id/button4"
        android:layout_width="80dp"
        android:layout_height="wrap_content"
        android:padding="10dp"
        android:text="="
        android:textSize="28dp"
        android:layout_alignParentBottom="true"
        android:layout_alignLeft="@+id/button16"
        android:layout_alignStart="@+id/button16" />

    <Button
        android:id="@+id/button9"
        android:layout_height="wrap_content"
        android:padding="10dp"
        android:text="7"
        android:textSize="28dp"
        android:layout_width="70dp"
        android:layout_above="@+id/button6"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true" />

    <Button
        android:id="@+id/button11"
        android:layout_height="wrap_content"
        android:padding="10dp"
        android:text="9"
        android:textSize="28dp"
        android:layout_width="70dp"
        android:layout_alignTop="@+id/button10"
        android:layout_toRightOf="@+id/button7"
        android:layout_toEndOf="@+id/button7" />

    <Button
        android:id="@+id/button10"
        android:layout_height="wrap_content"
        android:padding="10dp"
        android:text="8"
        android:textSize="28dp"
        android:layout_width="70dp"
        android:layout_alignTop="@+id/button9"
        android:layout_toRightOf="@+id/button9"
        android:layout_toEndOf="@+id/button9" />

    <Button
        android:id="@+id/button20"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:padding="10dp"
        android:text="←"
        android:textSize="28dp"
        android:layout_above="@+id/button14"
        android:layout_toRightOf="@+id/button8"
        android:layout_alignRight="@+id/button14"
        android:layout_alignEnd="@+id/button14" />

    <Button
        android:id="@+id/button19"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:padding="10dp"
        android:text="CE"
        android:textSize="28dp"
        android:layout_alignTop="@+id/button20"
        android:layout_toLeftOf="@+id/button20"
        android:layout_toStartOf="@+id/button20" />

    <Button
        android:id="@+id/button18"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:padding="10dp"
        android:text="±"
        android:textSize="28dp"
        android:layout_above="@+id/button11"
        android:layout_toLeftOf="@+id/button11"
        android:layout_toStartOf="@+id/button11" />

    <Button
        android:id="@+id/button17"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:padding="10dp"
        android:text="√"
        android:textSize="28dp"
        android:layout_alignTop="@+id/button18"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true" />

    <Button
        android:id="@+id/button14"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:padding="10dp"
        android:text="÷"
        android:textSize="28dp"
        android:layout_alignTop="@+id/button11"
        android:layout_alignParentRight="true"
        android:layout_alignParentEnd="true"
        android:layout_toRightOf="@+id/button5"
        android:layout_toEndOf="@+id/button5" />

    <Button
        android:id="@+id/button7"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:padding="10dp"
        android:text="5"
        android:textSize="28dp"
        android:layout_alignTop="@+id/button8"
        android:layout_toRightOf="@+id/button6"
        android:layout_toEndOf="@+id/button6" />

    <Button
        android:id="@+id/button6"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:layout_alignBaseline="@+id/button7"
        android:layout_alignBottom="@+id/button7"
        android:layout_alignParentLeft="true"
        android:padding="10dp"
        android:text="4"
        android:textSize="28dp"
        android:layout_marginRight="3dp"
        android:layout_marginBottom="3dp" />

    <Button
        android:id="@+id/button15"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:layout_alignBaseline="@+id/button7"
        android:layout_alignBottom="@+id/button7"
        android:layout_alignParentRight="true"
        android:padding="10dp"
        android:text="×"
        android:textSize="28dp"
        android:layout_marginBottom="3dp"
        android:layout_alignLeft="@+id/button14"
        android:layout_alignStart="@+id/button14" />

    <Button
        android:id="@+id/button8"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:padding="10dp"
        android:text="6"
        android:textSize="28dp"
        android:layout_above="@+id/button5"
        android:layout_alignLeft="@+id/button5"
        android:layout_alignStart="@+id/button5" />

    <Button
        android:id="@+id/button3"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:padding="10dp"
        android:text="2"
        android:textSize="28dp"
        android:layout_alignTop="@+id/button1"
        android:layout_toRightOf="@+id/button6"
        android:layout_toEndOf="@+id/button6" />

    <Button
        android:id="@+id/button1"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:padding="10dp"
        android:text="1"
        android:textSize="28dp"
        android:layout_above="@+id/button12"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true" />

    <Button
        android:id="@+id/button5"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:layout_alignBaseline="@+id/button3"
        android:layout_alignBottom="@+id/button3"
        android:layout_toRightOf="@+id/button7"
        android:padding="10dp"
        android:text="3"
        android:textSize="28dp"
        android:layout_marginBottom="3dp"
        android:layout_marginRight="3dp"/>

    <Button
        android:id="@+id/button16"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:layout_alignBaseline="@+id/button5"
        android:layout_alignBottom="@+id/button5"
        android:padding="10dp"
        android:text="-"
        android:textSize="28dp"
        android:layout_marginBottom="3dp"
        android:layout_alignRight="@+id/button2"
        android:layout_alignEnd="@+id/button2"
        android:layout_alignLeft="@+id/button15"
        android:layout_alignStart="@+id/button15" />

    <Button
        android:id="@+id/button2"
        android:layout_width="80dp"
        android:layout_height="wrap_content"
        android:layout_alignBaseline="@+id/button4"
        android:layout_alignBottom="@+id/button4"
        android:layout_alignParentRight="true"
        android:padding="10dp"
        android:text="+"
        android:textSize="28dp" />

    <Button
        android:id="@+id/button13"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:padding="10dp"
        android:text="."
        android:textSize="28dp"
        android:layout_alignTop="@+id/button4"
        android:layout_toRightOf="@+id/button3"
        android:layout_toEndOf="@+id/button3" />

    <Button
        android:id="@+id/button12"
        android:layout_width="70dp"
        android:layout_height="wrap_content"
        android:layout_alignBaseline="@+id/button13"
        android:layout_alignBottom="@+id/button13"
        android:layout_alignParentLeft="true"
        android:padding="10dp"
        android:text="0"
        android:textSize="28sp"
        android:layout_alignRight="@+id/button3"
        android:layout_alignEnd="@+id/button3" />

    <TextView
        android:id="@+id/textView1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignLeft="@+id/editText1"
        android:layout_alignParentTop="true"
        android:layout_alignRight="@+id/editText1"
        android:text=" "
        android:textSize="15dp"
        android:textAppearance="?android:attr/textAppearanceLarge"
        android:height="70dp" />

    <EditText
        android:id="@+id/editText1"
        android:layout_width="wrap_content"
        android:layout_height="210dp"
        android:ems="10"
        android:singleLine="true"
        android:textSize="28dp"
        android:layout_alignRight="@+id/button20"
        android:layout_alignEnd="@+id/button20"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
        android:height="70dp"
        android:layout_above="@+id/button20"
        android:layout_below="@+id/textView1" />

</RelativeLayout>


package com.example.mycalculator;

import android.app.Activity;

import android.app.Fragment;
import android.os.Bundle;
import android.view.LayoutInflater;
import android.view.Menu;
import android.view.MenuItem;
import android.view.View;
import android.view.ViewGroup;

import android.view.View.OnClickListener;
import android.widget.Button;
import android.widget.EditText;
import android.widget.TextView;


public class MainActivity extends Activity {
    private Button btn1,btn2,btn3,btn4,btn5,btn6,btn7,btn8,btn9,btn10,btn11,btn12,btn13,btn14,btn15,btn16,btn17,btn18,btn19,btn20;
    private EditText editText;//显示输入的数字
    private String opt = "+";//操作符
    private double n1 = 0.0, n2 = 0.0;//两个操作数
    private TextView textView;//显示算式

    //跟据被选择按钮的id设置监听器
    private OnClickListener lisenter = new OnClickListener() {

        @Override
        public void onClick(View v) {
            // TODO Auto-generated method stub
            editText = (EditText)findViewById(R.id.editText1);
            textView = (TextView) findViewById(R.id.textView1);
            String s = editText.getText().toString();//获取字符串
            Button btn =(Button)v;
            try{

                switch(btn.getId())
                {
                    case R.id.button1://1
                    {
                        String str = editText.getText().toString();
                        editText.setText(str + 1);
                        str = editText.getText().toString();
                        textView.setText(str);
                        break;
                    }
                    case R.id.button2://+
                    {
                        String str = editText.getText().toString();
                        n1 = Double.parseDouble(str);
                        opt = "+";
                        textView.setText(n1 + opt);
                        editText.setText("");
                        break;
                    }
                    case R.id.button3://2
                    {
                        String str = editText.getText().toString();
                        editText.setText(str + 2);
                        str = editText.getText().toString();
                        textView.setText(str);
                        break;
                    }
                    case R.id.button4://操作符=
                    {
                        if(opt == "+")
                        {
                            String str = editText.getText().toString();
                            n2 = Double.parseDouble(str);
                            textView.setText(n1 + opt + n2 + "=");
                            editText.setText((n1 + n2) + "");
                        }
                        else if(opt == "-")
                        {
                            String str = editText.getText().toString();
                            n2 = Double.parseDouble(str);
                            textView.setText(n1 + opt + n2 + "=");
                            editText.setText((n1 - n2) + "");
                        }
                        else if(opt == "*")
                        {
                            String str = editText.getText().toString();
                            n2 = Double.parseDouble(str);
                            textView.setText(n1 + opt + n2 + "=");
                            editText.setText((n1 * n2) + "");
                        }
                        else if(opt == "/")
                        {
                            String str = editText.getText().toString();
                            n2 = Double.parseDouble(str);
                            if(n2 == 0)
                            {
                                editText.setText("");
                                textView.setText("除数不能为0");
                                break;
                            }
                            else
                            {
                                textView.setText(n1 + opt + n2 + "=");
                                editText.setText((n1 / n2) + "");
                            }
                        }

                        break;
                    }
                    case R.id.button5://3
                    {
                        editText.setText(editText.getText().toString() + 3);
                        String str = editText.getText().toString();
                        textView.setText(str);
                        break;
                    }
                    case R.id.button6://4
                    {
                        editText.setText(editText.getText().toString() + 4);
                        String str = editText.getText().toString();
                        textView.setText(str);
                        break;
                    }
                    case R.id.button7://5
                    {
                        editText.setText(editText.getText().toString() + 5);
                        String str = editText.getText().toString();
                        textView.setText(str);
                        break;
                    }
                    case R.id.button8://6
                    {
                        editText.setText(editText.getText().toString() + 6);
                        String str = editText.getText().toString();
                        textView.setText(str);
                        break;
                    }
                    case R.id.button9://7
                    {
                        editText.setText(editText.getText().toString() + 7);
                        String str = editText.getText().toString();
                        textView.setText(str);
                        break;
                    }
                    case R.id.button10://8
                    {
                        editText.setText(editText.getText().toString() + 8);
                        String str = editText.getText().toString();
                        textView.setText(str);
                        break;
                    }
                    case R.id.button11://9
                    {
                        editText.setText(editText.getText().toString() + 9);
                        String str = editText.getText().toString();
                        textView.setText(str);
                        break;
                    }
                    case R.id.button12://0
                    {
                        textView.setText(n1 + opt + 10);
                        editText.setText(editText.getText().toString() + 0);
                        String str = editText.getText().toString();
                        textView.setText(str);
                        break;
                    }
                    case R.id.button13://.
                    {
                        String str = editText.getText().toString();
                        if(str.indexOf(".") != -1) //判断字符串中是否已经包含了小数点，如果有就什么也不做
                        {

                        }
                        else //如果没有小数点
                        {
                            if(str.equals("0"))//如果开始为0，
                                editText.setText(("0" + ".").toString());
                            else if(str.equals(""))//如果初时显示为空，就什么也不做
                            {

                            }
                            else
                                editText.setText(str + ".");
                        }
                        break;
                    }
                    case R.id.button14://操作符 /
                    {
                        String str = editText.getText().toString();
                        n1 = Double.parseDouble(str);
                        opt = "/";
                        editText.setText("");
                        textView.setText(n1 + opt);
                        break;
                    }
                    case R.id.button15://操作符*
                    {
                        String str = editText.getText().toString();
                        n1 = Double.parseDouble(str);
                        opt = "*";
                        editText.setText("");
                        textView.setText(n1 + opt);
                        break;
                    }
                    case R.id.button16://操作符-
                    {
                        String str = editText.getText().toString();
                        n1 = Double.parseDouble(str);
                        opt = "-";
                        editText.setText("");
                        textView.setText(n1 + opt);
                        break;
                    }
                    case R.id.button17://genhao
                    {
                        String str = editText.getText().toString();
                        n1 = Double.parseDouble(str);
                        if(n1 < 0)
                        {
                            editText.setText("");
                            textView.setText("负数没有平方根");
                        }
                        else
                        {
                            editText.setText(Math.sqrt(n1) + "");
                            textView.setText(n1 + "的平方根是");
                        }

                        break;
                    }
                    case R.id.button18://+/-
                    {
                        String str =editText.getText().toString();
                        n1 = Double.parseDouble(str);
                        if(str.length() > 0)
                            editText.setText(-n1 + "");
                        textView.setText(-n1 + "");
                        break;
                    }
                    case R.id.button19://CE
                    {
                        String str =editText.getText().toString();
                        if(str.length() > 0)
                            editText.setText("");
                        break;
                    }
                    case R.id.button20://<-
                    {
                        String str =editText.getText().toString();
                        if(str.length() > 0)
                            editText.setText(str.substring(0, str.length() - 1));
                        break;
                    }

                }
            }catch(Exception e){}
        }
    };

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        if (savedInstanceState == null) {
            getFragmentManager().beginTransaction()
                    .add(R.id.container, new PlaceholderFragment()).commit();
        }
        //获取按钮的id
        btn1 = (Button) findViewById(R.id.button1);
        btn2 = (Button) findViewById(R.id.button2);
        btn3 = (Button) findViewById(R.id.button3);
        btn4 = (Button) findViewById(R.id.button4);
        btn5 = (Button) findViewById(R.id.button5);
        btn6= (Button) findViewById(R.id.button6);
        btn7 = (Button) findViewById(R.id.button7);
        btn8 = (Button) findViewById(R.id.button8);
        btn9 = (Button) findViewById(R.id.button9);
        btn10 = (Button) findViewById(R.id.button10);
        btn11 = (Button) findViewById(R.id.button11);
        btn12 = (Button) findViewById(R.id.button12);
        btn13 = (Button) findViewById(R.id.button13);
        btn14 = (Button) findViewById(R.id.button14);
        btn15 = (Button) findViewById(R.id.button15);
        btn16 = (Button) findViewById(R.id.button16);
        btn17 = (Button) findViewById(R.id.button17);
        btn18 = (Button) findViewById(R.id.button18);
        btn19 = (Button) findViewById(R.id.button19);
        btn20 = (Button) findViewById(R.id.button20);
        //为按钮添加监听器
        btn1.setOnClickListener(lisenter);
        btn2.setOnClickListener(lisenter);
        btn3.setOnClickListener(lisenter);
        btn4.setOnClickListener(lisenter);
        btn5.setOnClickListener(lisenter);
        btn6.setOnClickListener(lisenter);
        btn7.setOnClickListener(lisenter);
        btn8.setOnClickListener(lisenter);
        btn9.setOnClickListener(lisenter);
        btn10.setOnClickListener(lisenter);
        btn11.setOnClickListener(lisenter);
        btn12.setOnClickListener(lisenter);
        btn13.setOnClickListener(lisenter);
        btn14.setOnClickListener(lisenter);
        btn15.setOnClickListener(lisenter);
        btn16.setOnClickListener(lisenter);
        btn17.setOnClickListener(lisenter);
        btn18.setOnClickListener(lisenter);
        btn19.setOnClickListener(lisenter);
        btn20.setOnClickListener(lisenter);
    }

    @Override
    public boolean onCreateOptionsMenu(Menu menu) {

        // Inflate the menu; this adds items to the action bar if it is present.
        getMenuInflater().inflate(R.menu.main, menu);
        return true;
    }

    @Override
    public boolean onOptionsItemSelected(MenuItem item) {
        // Handle action bar item clicks here. The action bar will
        // automatically handle clicks on the Home/Up button, so long
        // as you specify a parent activity in AndroidManifest.xml.
        int id = item.getItemId();
        if (id == R.id.action_settings) {
            return true;
        }
        return super.onOptionsItemSelected(item);
    }

    /**
     * A placeholder fragment containing a simple view.
     */
    public static class PlaceholderFragment extends Fragment {

        public PlaceholderFragment() {
        }

        @Override
        public View onCreateView(LayoutInflater inflater, ViewGroup container,
                                 Bundle savedInstanceState) {
            View rootView = inflater.inflate(R.layout.fragment_main, container,
                    false);
            return rootView;
        }
    }
}

