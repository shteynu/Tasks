# Tasks
Interesting tasks
package com.javarush.task.task05.task0529;

import java.io.BufferedReader;
import java.io.InputStreamReader;

/* 
Консоль-копилка
*/

public class Solution {
    public static void main(String[] args) throws Exception {
        BufferedReader bufferedReader = new BufferedReader(new InputStreamReader(System.in));
        int sum = 0;


        while (true) {

            String s = bufferedReader.readLine();

            if (s.equals("сумма")) {
                System.out.println(sum);
                break;
            } else {
                int a = Integer.parseInt(s);
                sum += a;
            }

        }

    }
}
