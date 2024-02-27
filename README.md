# 8-03 Стасенко Григорий Домашнее задание к занятию «GitLab» 8-03

## Задание 1
![image](https://github.com/Nightnek/git-8-3-hw/assets/127677631/f1855636-9d19-4efe-b533-c9c956dffe17)


---

## Задание 2
stages:
  - test
  - build

test:
  stage: test
  image: golang:1.17
  script: 
   - go test .

build:
  stage: build
  image: docker:latest
  script:
   - docker build .

![image](https://github.com/Nightnek/git-8-3-hw/assets/127677631/0030a3c9-4ecd-4f6f-94ae-49c9d31efd95)
![image](https://github.com/Nightnek/git-8-3-hw/assets/127677631/9fe638ca-78a8-4414-98c3-cb636d69bfbb)

---

