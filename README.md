# setup_in_ubuntu
## Cai dat vs code
- Đầu tiên các bạn vào trang chủ của VS Code: https://code.visualstudio.com/ sau đó tải về file có đuôi .deb
- cd Downloads
- sudo dpkg -i <tên_file_vừa_tải_về>.deb
- sudo apt-get install -f 

## upcode:
- create a new repository
- create folder: mkdir newfolder
- cap quyen: chown -R user:group folder
- cd newfolder
- mo vscode: code .
- new terminal
- echo "# ex_studychain" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/vuongdh/ex_studychain.git
- git push -u origin main

## up code khi co thay doi
- commit
- git push