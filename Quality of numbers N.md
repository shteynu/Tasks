# Tasks
Interesting tasks

package com.javarush.task.task05.task0532;

import java.io.*;

/* 
Задача по алгоритмам
*/

public class Solution {
    public static void main(String[] args) throws Exception {
        BufferedReader reader = new BufferedReader(new InputStreamReader(System.in));
        int maximum=Integer.MIN_VALUE;
        int N=Integer.parseInt(reader.readLine());
        int counter=N;

        while(counter>0) {

            N=Integer.parseInt(reader.readLine());
            if (N >= maximum) {
                maximum = N;
            }
            counter--;
        }
        System.out.println(maximum);
    }
}

