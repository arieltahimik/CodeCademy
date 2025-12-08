# Tasks  
**List Git branches**  
```
git branch
```
<br>

**Delete branches**  
```
# moma
# whitney

git branch -D moma
git branch -D whitney
```
<br>

**Create a new branch called unordered-list and switch over to it**
```
git branch unordered-list
git checkout unordered-list
```
<br>

**Replace paragraph with list**
```
<p>Description: Join Kay in celebrating their 29th birthday with free food and beverages, karaoke and a special appearance by Willy Nelson. Also, feel free to explore the Met museum before or after you stop by! Presents for Kay optional.</p>


<ul>
    <li>Join Kay in celebrating their 29th birthday with free food and beverages</li>
    <li>karaoke and a special appearance by Willy Nelson</li>
    <li>explore the Met museum before or after you stop by!</li>
    <li>Birthday presents optional</li>
</ul>
```
<br>

**Add index.html to the staging area**
```
git add index.html
```
<br>

**Make a commit**
```
git commit -m "Change paragraph to unordered list"
```
<br>

**Switch to main and merge unordered-list**
```
git checkout main
git merge unordered-list
```
<br>

