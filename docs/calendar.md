---
hide:
    - footer
    - navigation
---

<h1 style="text-align: center;">CALENDAR</h1>

## 1. About 
In this chapter, we will explore the relationship between days and dates in the context of our real-world calendar. We will also delve into the structure of weeks, months, years, and centuries, examining how they are interconnected with days and dates.

## 2. General Year vs Leap Year
We all know there are two types of years in our calendar: the general year and the leap year. In this section, we will explore these two types in depth and uncover the reasons behind their existence.

> **Do you know that there is a relation between the revolution of earth around the sun and these years ?**

### 2.1 Understanding the earth's revolution and calendar year
- We often hear that the Earth takes one year to revolve around the sun, and that's why the calendar changes. But that’s not entirely true!

- In reality, the Earth takes approximately 365 days, 5 hours, 48 minutes, and 12 seconds to complete one revolution around the sun. While some may not accept this, let’s assume it's accurate for this discussion. :)

- To simplify calculations, can we round 5 hours, 48 minutes, and 12 seconds to 6 hours?

- In a regular year, we move to the next year after 365 days, even though the Earth hasn't completed its full revolution. This means we're advancing to the next year 6 hours earlier than the actual revolution completion.

- As a result, there's a 6-hour gap between the calendar year and the Earth’s revolution each year.

- Over 4 years, these 6-hour differences add up to 24 hours, or one full day. Simple math, right?

- Therefore, after 4 years, there’s a one-day discrepancy between the Earth’s revolution and the calendar.

- To align the calendar with the Earth's revolution, we introduce a leap year, adding an extra day to the year, making it 366 days long.

- In essence, we add one extra day every 4 years, making the leap year a regular part of our calendar system.

### 2.2 Identifying a year type (General or Leap Year)
In this section, we will learn how to identify whether a given year is a general year or a leap year. From the previous section, we know that a leap year occurs every 4 years, so divisibility by 4 plays a key role in this identification.

**Example 1:**
Given the year 1996, the task is to determine if it's a general or leap year. Simply check if 1996 is divisible by 4. Since it is, 1996 is a leap year.

> **Do you know century year doesn't follow the above stated rule of identifying the year type ?**

#### 2.2.1 Identifying a century year type
- For century years, the standard leap year rule (every 4 years) does not apply.

- Instead, century years follow a special rule: only every 4th century is a leap year, meaning the year must be divisible by 400.

    **Example 2:**
    Consider the year 2100, a century year. To determine whether 2100 is a leap year or a general year, we check if it is divisible by 400. Since it's not, 2100 is not a leap year. 
    Interesting, right ? :)

#### 2.2.2 Understanding math behind 400 rule
- Remember in section 2.1, we rounded 5 hours, 48 minutes, and 12 seconds to 6 hours?

- By rounding, we ignored a gap of 11 minutes and 48 seconds, which equals 0.0075 days. Don’t believe it? Try converting it yourself! 😉

- This small gap means the calendar is behind the Earth's revolution by 0.0075 days each year. It seems negligible, right? But it adds up!

- Over 400 years, this gap totals 3 days—quite surprising, isn’t it?

- To account for this 3-day difference, we skip 3 leap years across 4 centuries.

- This is why only every 4th century is a leap year.

## 3. Odd Days [0,6]
The number of days exceeding complete weeks in a given period are called **Odd Days**. The possible range for odd days is 0 to 6.

**Example 3:**

⇒ For 50 days: Here, we can form 7 complete weeks with 49 days and 1 day will left out. Hence, there is **1 odd day** in 50 days.

⇒ For 76 days: Here, we can form 10 complete weeks with 70 days and 6 days will left out. Hence, there are **6 odd days** in 76 days.

> To find the number of odd days for any number of days, simply divide by 7 and take the remainder. The remainder is the number of odd days.

Now, let's explore this further!

### 3.1 Finding odd days in months of the year
Months can have 31, 30, 29, or 28 days. Let's calculate the odd days for each type:

- 31-day month: 31 days = 4 complete weeks + **3 odd days**.

- 30-day month: 30 days = 4 complete weeks + **2 odd days**.

- 29-day month: 29 days = 4 complete weeks + **1 odd day** (February in a leap year).

- 28-day month: 28 days = 4 complete weeks + **0 odd days** (February in a general year).

### 3.2 Finding odd days in ```General Year``` & ```Leap Year```
There are two types of years: general years and leap years.

- General Year (365 days): 365 ÷ 7 = 1 remainder, so there is **1 odd day** in a general year.

- Leap Year (366 days): 366 ÷ 7 = 2 remainder, so there are **2 odd days** in a leap year.

### 3.3 Finding odd days in certain years < 100
To find odd days in any number of years less than 100, we need to account for both general and leap years.

**Example 4:** For 43 years:

⇒ There are 10 leap years (10 × 2 odd days = 20 odd days) and

⇒ 33 general years (33 × 1 odd day = 33 odd days).

⇒ Total odd days = 53.

⇒ Since odd days range from 0 to 6, divide 53 by 7. The remainder is 4.

⇒ Thus, there are **4 odd days** in 43 years.

> **Alternate Method**: Simply add the number of leap years to the given years. For 43 years, we add 10 leap years in given 43 years to get 53 odd days. Dividing 53 by 7 gives a remainder of 4, confirming **4 odd days**.

### 3.4 Finding odd days in centuries
As we know from the special case (refer to Section 2.2.2), for a century to be a leap year, only every 4th century qualifies as a leap year.

**Example 5:**
Out of the 100th, 200th, 300th, and 400th years, only the 400th is a leap year. Similarly, future century leap years will be 800, 1200, 1600, 2000, 2400, and so on.

> **Note**: In Section 2, we explored the synchronization between the Earth's revolution around the Sun and the calendar. We concluded that this synchronization occurs every 400 years. Therefore, each 400-year period is identical. E.g. Period from 1st year to 400th year is identical to period from 401th year to 800th year and it continues.

What we've learned so far is that we only need to find the odd days in the first four centuries (100, 200, 300, 400), as this pattern repeats every 400 years.

#### 3.4.1 Finding odd days in 100 years
- The first key point is the number of leap years in 100 years. There are 24 leap years because the 100th year is not a leap year (as it's a non-leap century).

- To find the odd days in 100 years (with 24 leap years):
    - Total odd days = 100 (days) + 24 (leap years) = 124 odd days.

    - To reduce the number in range of 0 to 6 divide 124 by 7, which gives a remainder of 5.

- Therefore, there are **5 odd days** in the first century.

- This pattern is identical for the 500th, 900th, 1300th, 1700th, 2100th centuries, and so on.

#### 3.4.2 Finding odd days in 200 years
- The number of odd days from the 1st to the 100th period is 5, as noted in Section 3.4.1.

- Now, let’s focus on the period from the 101st to the 200th year.

- The number of leap years in this period will also be 24, since the 200th year is a non-leap century.

- The method for finding the odd days from the 101st to the 200th year is the same as in Section 3.4.1.

- Therefore, in the complete 200-year period, we have a total of 10 odd days, which can be optimized in odd days range as 10/7, resulting in a remainder of 3.

- Thus, there will be **3 odd days** in the 200 years.

- This pattern is identical for the 600th, 1000th, 1400th, 1800th, 2200th centuries, and so on.

#### 3.4.3 Finding odd days in 300 years
- The number of odd days from the 1st to the 200th period is 3, as stated in Section 3.4.2.

- Now, let’s focus on the period from the 201st to the 300th year.

- The number of leap years in this period will again be 24, since the 300th year is a non-leap century.

- The method for finding odd days from the 201st to the 300th year is the same as in Section 3.4.1.

- Thus, in the complete 300-year period, we have a total of 8 odd days, which can be optimized n odd days range as 8/7, resulting in a remainder of 1.

- Therefore, there will be **1 odd day** in the 300 years.

- This pattern is identical for the 700th, 1100th, 1500th, 1900th, 2300th centuries, and so on.

#### 3.4.4 Finding odd days in 400 years
- The number of odd days from the 1st to the 300th period is 1, as noted in Section 3.4.3.

- Now, let's focus on the period from the 301st to the 400th year.

- The number of leap years in this period will be 25, as the 400th year is a leap year century.

- To find the odd days in the period from the 301st to the 400th year, with 25 leap years:

    - Odd days in 100 years = 100 + 25 (leap years) = 125.

    - This gives 125 odd days, which can be optimized to odd days range as 125/7, resulting in a remainder of 6.

- Therefore, in the complete 400-year period, we have a total of 7 odd days (6 + 1), which further optimizes to odd days range as 7/7, yielding a remainder of 0.

- Thus, there will be **0 odd day** in the 400 years.

- This pattern is identical for the 800th, 1200th, 1600th, 2000th, 2400th centuries, and so on.

**Example 6:** 
Find the number of odd days in 1700 years : 

⇒ 1700 years

⇒ 1600 years + 100 years

⇒ 400 years x 4 + 100 years (intention of multiple of 400)

⇒ 0 x 4 + 5 odd days

⇒ **5 odd days**

(*400 years have 0 odd days and 100 years have 5 odd days*)

**Example 7**: 
Find the number of odd days in 2300 years :

⇒ 2300 years

⇒ 2000 years + 300 years (intention of multiple of 400)

⇒ 400 years x 5 + 300 years

⇒ 0 x 5 + 1 odd days

⇒ **1 odd day**

(*400 years have 0 odd days and 300 years have 1 odd day*)


## 4. Dedicated days for Odd Days Range
The range of odd days is from 0 to 6. In the real calendar, each odd day corresponds to a specific day of the week. The table below shows the mapping of odd days to their respective days of the week:

<div style="text-align: center;">
    <table style="display: flex; justify-content: center; margin: 0 auto;">
        <tr>
            <th> Odd Day </th>
            <th> Dedicated Day of Week </th>
        </tr>
        <tr>
            <td> 0 </td>
            <td> Sunday </td>
        </tr>
        <tr>
            <td> 1 </td>
            <td> Monday </td>
        </tr>
        <tr>
            <td> 2 </td>
            <td> Tuesday </td>
        </tr>
        <tr>
            <td> 3 </td>
            <td> Wednesday </td>
        </tr>
        <tr>
            <td> 4 </td>
            <td> tdursday </td>
        </tr>
        <tr>
            <td> 5 </td>
            <td> Friday </td>
        </tr>
        <tr>
            <td> 6 </td>
            <td> Saturday </td>
        </tr>
    </table>
    <h6 style="text-align: center;">(Table 1.1)</h6>
</div>

The first day of the calendar, Monday (01/01/0001), corresponds to 1 odd day. Hence, in the table 1.1 the monday was dedicated to odd day no. 1.

## 5. Understanding the repitition of calendar
Sometimes the question is asked based upon the repitition of the calendar. Saying two calendar same means the day on each and every date of a calendar is same in another calendar. Below are the listed conditions for making two calendars same :
- Both the calendar should be of same type like either both should be general year or leap year.
- The day on 1st January of both calendars should be same, OR
- The number of odd days between the 1st Jan of calendars should be zero.

**Example: 8** Find the calendar year which is same as 2002 - 
a) 2008
b) 2010
c) 2013
d) 2012

Solution - The year 2002 is a general year, so we need to find another general year with the same calendar.

- Option a) 2008 is a leap year, so it can't be the correct answer.

- Now, calculating the number of odd days from 1st Jan 2002 to 1st Jan 2010 gives 3 odd days, which doesn't match the condition for the same calendar.

- However, calculating the odd days from 1st Jan 2002 to 1st Jan 2013 gives 0 odd days, fulfilling the condition.
**Thus, the answer is a) 2013**.

