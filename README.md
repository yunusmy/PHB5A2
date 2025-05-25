1. What is PostgreSQL?

ANS :-
PostgreSQL একটি শক্তিশালী এবং ব্যবসা-স্তরের ওপেন সোর্স রিলেশনাল ডাটাবেস। এটি রিলেশনাল এসকিউএল এবং নন-রিলেশনাল JSON ডেটা এবং কোয়েরি ব্যবহারের অনুমতি দেয়।

5. Explain the purpose of the `WHERE` clause in a `SELECT` statement.
   ANS:-
   WHERE ক্লজ ব্যবহার করে নির্দিষ্ট শর্ত অনুযায়ী ডেটা ফিল্টার করা যায়।
   <!-- SELECT * FROM user WHERE age >=18; -->

6. How can you calculate aggregate functions like `COUNT()`, `SUM()`, and `AVG()` in PostgreSQL

ANS:- এই ফাংশনগুলো ডেটা গণনা, যোগফল, এবং গড় বের করতে ব্যবহৃত হয়

<!-- SELECT COUNT(*) FROM students; -->

SELECT SUM(salary) FROM employees;
SELECT AVE(marks) FROM exams;
