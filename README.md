# playGradle [![Build Status](https://travis-ci.org/Prussia/playGradle.svg?branch=master)](https://travis-ci.org/Prussia/playGradle)
Personal Project to practice and record the examples on Gradle and Travis

* The resolution for .gradlew: permission denied 
  ```
  git update-index --chmod=+x gradlew
  git commit -m "permission access for travis"
  git ls-tree HEAD
  ```
  Or
  
  ```
  before_install:
 	- chmod +x gradlew
  ```