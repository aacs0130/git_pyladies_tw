###This is a practice for team work in Pyladies TW 2018.
After practicing this, you will know how to do team work with others and solve conflict.

We have 2 roles to collabrate in this demo: fish and cat. Please modify colors in order rainbow.txt 
### Fish's steps
1. git checkout fish##
2. Add Red\n and Green\n in rainbow.txt
3. git commit -m "add red and green"
4. git checkout dev##
5. git merge fish##
6. (Wait cat's step 1)
7. git push
8. Add Orange\n in rainbow.txt
9. git commit -m "add orange"
10. (Wait cat's step 9)
11. git checkout dev##
12. git merge fish##
13. ....solve conflict...
14. git commit -m "Fish solve conflict"
15. git push

### Cat's steps
1. git checkout cat##
2. Add Yellow\n and Blue\n in rainbow.txt
3. git commit -m "add yellow and blue"
4. (Wait fish finished it's step 7)
5. git checkout dev##
6. git merge cat##
7. ....solve conflict...
8. git commit -m "Cat solve conflict"
9. git push
10. git checkout cat##
11. git merge dev##
12. Add Purple\n in rainbow.txt
13. git commit -m "add purple"
14. git checkout dev##
15. git merge cat##
16. git push
