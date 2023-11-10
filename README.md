package com.example.myapplication;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.TextView;

public class MainActivity extends AppCompatActivity implements View.OnClickListener {
    TextView textView;
    Button button;


    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        textView = (TextView) findViewByld(R.id.textView);
        button = (Button) findViewByld(R.id.button);
        button.setOnClickListener(view -> textView.setText("Sorry, but you dont't fit"));

    }

    private Object findViewByld(int textView) {
        return null;
    }

    @Override
    public void onClick(View view) {

    }
}
# Android-Studiuo-lesson1
