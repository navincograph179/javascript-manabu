# JavaScript Basics - Exercises and Answers

This document contains **basic to intermediate JavaScript exercises** along with their **answers**. Each question is provided in both **English** and **Japanese**.

---

## Table of Contents
1. [Variables (変数)](#variables)
2. [Data Types (データ型)](#data-types)
3. [Operators (演算子)](#operators)
4. [Comments (コメント)](#comments)
5. [Conditional Statements (条件文)](#conditional-statements)
6. [Loops (ループ)](#loops)
7. [Functions (関数)](#functions)
8. [Arrays (配列)](#arrays)
9. [Objects (オブジェクト)](#objects)
10. [`this` Keyword (`this` キーワード)](#this-keyword)

---

## 1. Variables (変数) <a name="variables"></a>

### Question 1  
Declare a variable `name` and assign it your name. Print it to the console.  
(変数 `name` を宣言し、自分の名前を代入してください。コンソールに出力してください。)

### Question 2  
Declare three variables: `firstName`, `lastName`, and `age`. Combine them into a single string like `"John Doe is 25 years old."` and print it.  
(3つの変数 `firstName`, `lastName`, `age` を宣言し、`"John Doe is 25 years old."` のような文字列に結合して出力してください。)

---

## 2. Data Types (データ型) <a name="data-types"></a>

### Question 1  
Create a variable `isRaining` and set it to `true`. Print its data type using `typeof`.  
(変数 `isRaining` を作成し、`true` を代入してください。`typeof` を使ってそのデータ型を出力してください。)

### Question 2  
Create a variable `mixedData` and assign it an array with different data types: `["Alice", 25, true, null]`. Loop through the array and print the data type of each element.  
(変数 `mixedData` を作成し、異なるデータ型の配列 `["Alice", 25, true, null]` を代入してください。配列をループして、各要素のデータ型を出力してください。)

---

## 3. Operators (演算子) <a name="operators"></a>

### Question 1  
Use the addition operator to add two numbers and print the result.  
(加算演算子を使って2つの数字を足し、結果を出力してください。)

### Question 2  
Write a program that checks if a number is divisible by both 3 and 5 using logical operators.  
(論理演算子を使って、ある数字が3と5の両方で割り切れるかどうかをチェックするプログラムを書いてください。)

---

## 4. Comments (コメント) <a name="comments"></a>

### Question 1  
Write a program to calculate the area of a circle. Add comments to explain each step.  
(円の面積を計算するプログラムを書いてください。各ステップを説明するコメントを追加してください。)

### Question 2  
Write a program to calculate the factorial of a number. Add comments to explain the logic.  
(ある数字の階乗を計算するプログラムを書いてください。ロジックを説明するコメントを追加してください。)

---

## 5. Conditional Statements (条件文) <a name="conditional-statements"></a>

### Question 1  
Write a program that checks if a number is positive or negative.  
(ある数字が正か負かをチェックするプログラムを書いてください。)

### Question 2  
Write a program that takes a number and prints "Fizz" if it's divisible by 3, "Buzz" if it's divisible by 5, and "FizzBuzz" if it's divisible by both.  
(ある数字が3で割り切れる場合は "Fizz"、5で割り切れる場合は "Buzz"、両方で割り切れる場合は "FizzBuzz" を出力するプログラムを書いてください。)

---

## 6. Loops (ループ) <a name="loops"></a>

### Question 1  
Use a `for` loop to print numbers from 1 to 10.  
(`for` ループを使って、1から10までの数字を出力してください。)

### Question 2  
Use a `while` loop to find the sum of all even numbers between 1 and 50.  
(`while` ループを使って、1から50までの偶数の合計を求めてください。)

---

## 7. Functions (関数) <a name="functions"></a>

### Question 1  
Write a function called `greet` that takes a name as a parameter and prints `"Hello, [name]!"`.  
(`greet` という関数を作成し、名前を引数として受け取り、`"Hello, [name]!"` を出力してください。)

### Question 2  
Write a function called `isPrime` that takes a number and returns `true` if it's a prime number, otherwise `false`.  
(`isPrime` という関数を作成し、ある数字が素数であれば `true`、そうでなければ `false` を返してください。)

---

## 8. Arrays (配列) <a name="arrays"></a>

### Question 1  
Create an array of your favorite fruits and print the second item.  
(好きなフルーツの配列を作成し、2番目の要素を出力してください。)

### Question 2  
Write a program that removes all duplicate values from an array. For example, `[1, 2, 2, 3]` should become `[1, 2, 3]`.  
(配列から重複する値を削除するプログラムを書いてください。例えば、`[1, 2, 2, 3]` は `[1, 2, 3]` になります。)

---

## 9. Objects (オブジェクト) <a name="objects"></a>

### Question 1  
Create an object called `book` with properties `title`, `author`, and `year`. Print the object.  
(`book` というオブジェクトを作成し、`title`, `author`, `year` というプロパティを追加してください。オブジェクトを出力してください。)

### Question 2  
Add a method called `getSummary` to the `book` object that returns a string like `"The book [title] was written by [author] in [year]."`.  
(`book` オブジェクトに `getSummary` というメソッドを追加し、`"The book [title] was written by [author] in [year]."` のような文字列を返してください。)

---

## 10. `this` Keyword (`this` キーワード) <a name="this-keyword"></a>

### Question 1  
Create an object called `person` with properties `name` and `age`. Add a method called `greet` that prints `"Hello, my name is [name]."`.  
(`person` というオブジェクトを作成し、`name` と `age` というプロパティを追加してください。`greet` というメソッドを追加し、`"Hello, my name is [name]."` を出力してください。)

### Question 2  
Create an object called `calculator` with methods `add`, `subtract`, `multiply`, and `divide`. Each method should take two numbers and return the result. Use `this` to refer to the object's properties.  
(`calculator` というオブジェクトを作成し、`add`, `subtract`, `multiply`, `divide` というメソッドを追加してください。各メソッドは2つの数字を受け取り、結果を返します。`this` を使ってオブジェクトのプロパティを参照してください。)

---