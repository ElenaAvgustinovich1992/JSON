## 1. Create a remote repository called JSON.


## 2. Clone the ```JSON``` repository to the local computer.
We used ```git clone``` command. 
```
~/Git 
git clone https://github.com/ElenaAvgustinovich1992/JSON.git 
```
## 3. Create a ```new.json``` file inside the local JSON.
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
## 7. Edit the content of the file ```new.json```- write information about yourself (full name, age, number of pets, future desired salary). Write everything in JSON format.
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
~/Git/JSON    main !2   
git add .
```
Then
```
~/Git/JSON    main +2   
git commit -m "add new.json"  
```
Then 
```
~/Git/JSON    main ⇡1 !1   
git push 
```
## 9. Create a ```preferences.json file```.
```
~/Git/JSON    main !1   
touch preferences.json 
```
## 10. In the ```preferences.json file```, add information about your preferences (favorite movie, favorite series, favorite food, favorite season, country you would like to visit) in JSON format.
```
~/Git/JSON    main !1 ?1   
nano preferences.json 

{

"favorite movie":"Ice",
"favorite series":"nope",
"favorite food":"sushi",
"favorite season":"summer",
"country you would like to visit":"London"

}
```
## 11. Create a file ```sklls.json``` add information about the skills that will be studied in the course in JSON format
```
~/Git/JSON    main !1 ?2   
cat>sklls.json

 {
"Hard skills": [
"Postman",
"SQL",
"GIT",
"Linux",
"Charles Proxy"],

"Soft skills":[
"Communicative",
"Quick learn",
"Team player"]

}
```
## 12. Send 2 files at once to an remote repository.
```
~/Git/JSON    main +3   
git add . && git commit -m "add two files" skills.json 
preferences.json && git push origin main    
```
## 13. Create the bug_report.json file at the web interface.
## 14. Save the changes at the web interface.
## 15. At the web interface, modify the bug_report.json file and add the bug report in JSON format.
## 16. Save the changes at the web interface.
## 17. Synchronize remote and local JSON repository.
```
~/Git/JSON    main ⇡1   
git pull origin main 
```