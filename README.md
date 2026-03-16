# Python-activity-2
Activity 2 - Team 23 

# Python Programming Tasks

## Case Study Title

Create a set of sports played by students, add new sports introduced this year, find common sports with another school using intersection, and display all sports using union.

---

## Student Details

**USN:**
24BCAR0477
24BCAR0499
24BCAR0478
24BCAR0518

**Name:**
Pavan S
Sharuni M Lathesh
Pinky RK
Syed Hassan

---

# PROGRAM 1

## Algorithm

Step 1: Start the program.
Step 2: Create a set containing sports played by students.
Step 3: Store sports like Cricket, Football, Badminton, etc.
Step 4: Display the set of sports.
Step 5: Stop the program.

## Code

```python
sports = {"Cricket", "Football", "Badminton", "Basketball"}

print("Sports played by students:")
print(sports)
```

## Output

```
Sports played by students:
{'Cricket', 'Football', 'Badminton', 'Basketball'}
```

---

# PROGRAM 2

## Algorithm

Step 1: Start the program.
Step 2: Create a set containing sports played by students.
Step 3: Add new sports introduced this year using `add()`.
Step 4: Display the updated set of sports.
Step 5: Stop the program.

## Code

```python
sports = {"Cricket", "Football", "Badminton", "Basketball"}

sports.add("Tennis")
sports.add("Hockey")

print("Sports played by students after adding new:")
print(sports)
```

## Output

```
Sports played by students after adding new:
{'Cricket', 'Football', 'Badminton', 'Basketball', 'Tennis', 'Hockey'}
```

---

# PROGRAM 3

## Algorithm

Step 1: Start the program.
Step 2: Create a set of sports played in our school.
Step 3: Create another set of sports played in another school.
Step 4: Use `intersection()` to find common sports.
Step 5: Display the common sports.
Step 6: Stop the program.

## Code

```python
school1 = {"Cricket", "Football", "Badminton", "Basketball", "Tennis"}
school2 = {"Football", "Hockey", "Cricket", "Tennis"}

common = school1.intersection(school2)

print("Common sports in both schools:")
print(common)
```

## Output

```
Common sports in both schools:
{'Tennis', 'Cricket', 'Football'}
```

---

# PROGRAM 4

## Algorithm

Step 1: Start the program.
Step 2: Create a set of sports played in our school.
Step 3: Create a set of sports played in another school.
Step 4: Use `union()` to combine all sports from both schools.
Step 5: Display the combined sports set.
Step 6: Stop the program.

## Code

```python
school1 = {"Cricket", "Football", "Badminton", "Tennis"}
school2 = {"Football", "Hockey", "Tennis"}

common = school1.union(school2)

print("All sports from both school:")
print(common)
```

## Output

```
All sports from both school:
{'Football', 'Badminton', 'Hockey', 'Tennis', 'Cricket'}
```

---

# Result

The Python programs successfully demonstrate set operations such as creating sets, adding elements, finding common elements using intersection, and combining sets using union.
