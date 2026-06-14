Kien thuc buoi 3
A. Cac cau lenh giua cac vung: 
- Chuyen file tu vung Working Directory sang vung Staging: git add <ten file>
- Chuyen file tu vung Staging sang Repository: git commit -m<ten commit> 
- Chuyen file tu vung Staging quay tro lai vung Working Directory: 
+ Chuyen 1 specific file: git restore --staged <ten file> 
+ Chuyen tat ca: git restore --staged . 
- Chuyen file tu vung Respository ve vung Working Directory: git reset HEAD ~ <so commit>

B. Branching 
- Main
- Branches

- Tao new branch: git branch <ten branch>
- Switch branches: git checkout <ten branch muon sang>
- Xoa branch: 
+ Switch sang branch khac
+ Cau lenh: git branch -D <ten branch muon xoa >
#Note: Luon pull code truoc khi tao new branch

C. Gitignore files
- Dung de save nhung files khong duoc theo doi boi git
- Tao file: .gitignore 
- Cach comment trong gitignore: dung *

D. Convention
- snake_case
- kebab-case
- camelCase
- PascalCase

E. Review cach khai bien
- let <ten bien> = "<text>"; 
- const <ten bien> = "<text>"; 

F. Object 
- key: <valude>

G. Array
- arr = [ giaTri1, giaTri2, giaTri3]
- Count tu 0 
- arr.length

H. Function
- function <ten phep tinh> (<kieu du lieu>) {
    if 
    else
}

I. Array with for
- arr = [giaTri1, giaTri2, giaTri3];

for (let i = 0; i < arr.length; i++) {
    console.log(arr[i]);
}   


F. Git Amend
- Sua commit cuoi cung: git commit --amend -m"<new message>"
- Hoac: 
+ git commit --amend
+ esc + Insert
+ :wq + enter

- Them file vao commit cuoi cung: 
+ git add <ten file>
+ git commit --amemd --no-edit
+ git commit --amend -m"<new message>"
