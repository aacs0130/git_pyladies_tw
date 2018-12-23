### This is a practice for team work in Pyladies TW 2018.
After practicing this, you will know how to do team work with others and solve conflict.

We have 2 roles to collabrate in this demo: fish and cat. Please modify colors in order rainbow.txt 
### Fish's steps
1. git checkout fish##
2. Add Red\n and Green\n in rainbow.txt
3. git commit -m "add red and green
4. git merge dev##
5. git checkout dev##
6. (Wait cat's step 1)
7. git merge fish##
8. git push
9. Add Orange\n in rainbow.txt
10. git commit -m "add orange"
11. (Wait cat's step 16)
12. git merge dev##
13. ....solve conflict...
14. git commit -m "Fish solve conflict"
15. git push
16. git checkout dev##
17. git merge fish##
18. git push

### Cat's steps
1. git checkout cat##
2. Add Yellow\n and Blue\n in rainbow.txt
3. git commit -m "add yellow and blue"
4. (Wait fish's step 8)
5. git merge dev##
6. ....solve conflict...
7. git commit -m "Cat solve conflict"
8. git push
9. git checkout dev##
10. git merge cat##
11. git checkout cat##
12. Add Purple\n in rainbow.txt
13. git commit -m "add purple"
14. git checkout dev##
15. git merge cat##
16. git push
