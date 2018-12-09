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
6. git push
6. Add Orange\n in rainbow.txt
7. git commit -m "add orange"
8. (Wait cat's step 9)
9. git checkout dev##
10. git merge fish##
11. ....solve conflict...
12. git commit -m "Fish solve conflict"
13. git push

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
9. git checkout cat##
10. Add Purple\n in rainbow.txt
11. git commit -m "add yellow and blue"
12. git checkout dev##
13. git merge cat##
14. git push
