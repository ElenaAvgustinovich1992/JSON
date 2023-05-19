## 1. Create a remote repository called JSON.


## 2. Clone the JSON repository to the local computer.
We used ```git clone``` command. 
```
~/Git 
git clone https://github.com/ElenaAvgustinovich1992/JSON.git 
```
## 3. Create a new.json file inside the local JSON.
```
~/Git/JSON    main    
touch new.json 
```
## 4. Add the file to Git.
```
~/Git/JSON    main !1 ?1    
git add . 
```
## 5. Commit the file.
```
~/Git/JSON    main +2    
git commit -m "add new.json file"                                                                         ✔ 
[main 79d78e7] add new.json file
2 files changed, 18 insertions(+), 1 deletion(-)
create mode 100644 new.json
```
## 6. Send the file to a remote GitHub repository.
```
~/Git/JSON    main ⇡1 !1   
git push
```
## 7. Edit the content of the file new.json - write information about yourself (full name, age, number of pets, future desired salary). Write everything in JSON format.
```
~/Git/JSON    main !1   
nano new.json 

{

"full name":"Lena Avgustinovich",
"age":30,
"number of pets":4,
"expected salary in the future":7000

}
```
## 8. Send the changes to a remote repository.
```

```

