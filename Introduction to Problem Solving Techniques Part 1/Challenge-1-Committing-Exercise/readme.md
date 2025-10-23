# Challenge 1 Committing Exercise

1. Create a new folder named `Garage`.

2. Initialize a new Git repository inside the `Garage` folder.
    - Make sure you are not already inside another Git repository.
    - Example:
      ```
      cd Garage
      git init
      ```

3. Create two new files: `Ferrari.txt` and `Lamborghini.txt` (initially empty).

4. Create a commit that adds both empty files with the commit message:
    - "create my car in garage lists"
    - Example:
      ```
      git add Ferrari.txt Lamborghini.txt
      git commit -m "create my car in garage lists"
      ```

5. In `Ferrari.txt`, add the following lines:
    - This car was purchased on xx/xx/xxxx
    - This car was purchased for x9,876,543

6. In `Lamborghini.txt`, add the following lines:
    - This car was purchased on xx/xx/xxxx
    - This car was purchased for x9,999,999

7. Create a commit that includes changes to `Ferrari.txt` only, with the message:
    - "Added recording of purchase information and price of Ferrari cars."

8. Create a commit that includes changes to `Lamborghini.txt` only, with the message:
    - "Added recording of purchase information and price of Lamborghini cars."

9. Append this line to the end of `Ferrari.txt`:
    - This car is red

10. In `Lamborghini.txt`, add a line at the very top and a line at the very bottom:
     - First line (top): Currently using this car
     - Last line (bottom): This car is green

11. Commit the changes to both files with the message:
     - "Add a record of the colors of both cars and the current car."

12. Show the list of all commits using a Git command — you should see exactly 4 commits.
     - Example:
        ```
        git log --oneline
        ```

Attach a screenshot of the commit history below when done.
