# BigData2020UTM (Big data class).
---
### Explain the impact of data today.

#### The data is important today because thanks to them you can obtain accurate and clear information, which helps us avoid making wrong decisions and being able to visualize the best options to choose to reach our goals. and in turn it helps us to solve the problems that appear in the course of the aforementioned goals.
---
### Explain the causes for which data generation has increased.

#### The generation of data has been increasing these days due to the high demand of the same given by the office workers, doctors, computer scientists, etc. Well, these increasingly need more information to perform their daily tasks which involve many devices which are generating the aforementioned data.
---
### Define the concept of Big Data.

#### Big data is a combination of structured, semi-structured and unstructured data collected by organizations that can be extracted for information and used in machine learning projects, predictive modeling and other advanced analysis applications.
---
### Differentiate between open data and private data.

#### "Open data" is licensed digital information so that it is available to anyone for free so they can use and publish them as they wish, without copyright restrictions. In contrast, closed data often restricts use, linking it to the license due to security or privacy considerations.
---
### Differentiate between structured and unstructured data.

#### Structured data is highly organized and formatted so that it can be easily searched in relational databases. Unstructured data does not have a predefined format or organization, which makes it much more difficult to collect, process and analyze.
---
### Differentiate between stored data and moving data.

#### The stored data are those that are structured and that are used for their analysis and the generation of information. On the other hand, data in motion is data which is being transmitted in a network. The biggest threat to this type of data is the interceptions and alterations that they may suffer.
---
### Define the meaning of data analysis.
#### Data analysis is a process of inspection, cleaning, transformation and modeling of data with the aim of discovering useful information, informing the conclusion and supporting decision making.
---
### Explain the impact of data analysis in organizations.

#### Data analysis impacts organizations in such a way that without doing such an action it would be very difficult to organize the data and turn it into useful information for the organization and consequently it would make decision making difficult.
---
### Explain the different types of data analysis.

#### Descriptive Analysis:
##### The first type of data analysis is descriptive analysis. It is at the base of all data information. It is the simplest and most common use of data in today's business. The descriptive analysis responds to "what happened" by summarizing the data passed generally in the form of panels.

#### Diagnostic analysis:
##### The diagnostic analysis takes the information found in the descriptive analysis and deepens to find the cause of that result. Organizations make use of this type of analysis, as it creates more connections between the data and identifies patterns of behavior.

#### Predictive Analysis:
##### This type of analysis is another step forward in descriptive and diagnostic analyzes. Predictive analysis uses the data we have summarized to make logical predictions of event results. This analysis is based on statistical models, which require additional technology and labor to forecast. It is also important to understand that the forecast is only an estimate; The accuracy of the predictions depends on the quality and detailed data.

#### Prescriptive Analysis:
##### The last type of data analysis is the most sought after, but few organizations are really equipped to do it. The prescriptive analysis is the frontier of the data analysis, combining the knowledge of all the previous analyzes to determine the course of action to be taken in a current problem or decision. Prescriptive analysis uses cutting-edge technology and data practices. It is a great organizational commitment and companies must be sure that they are ready and willing to contribute effort and resources.
---
### Hadoop:
#### It is an open source software structure for storing data and running applications in commercial hardware clusters, it provides massive storage for any type of data, huge processing power and the ability to process virtually concurrent tasks or jobs. unlimited
---
### MapReduce
#### It is a framework that provides a parallel and distributed data processing system and is composed of 2 "Map and Reduce" processes where:
##### Map extracts and assigns values to certain keys for a single document and Reduces accumulates and combines the keys of multiple documents to create a unique reduced value for each key from the multiple values generated.
---
### Docker containers.
#### These are lightweight and portable containers for software applications and these can be run on any machine that has Docker installed, regardless of the operating system that the machine has below.
---
### Apache Spark.
#### It is a programming framework for distributed data processing designed to be fast and general purpose, this can be considered as an evolution of Apache Hadoop, which does not take full advantage of distributed processing capabilities, without having to write to disk and instead use RAM.
---
### Arquitechture Lambda & Kappa.
#### the main difference between both architectures is the data processing flows involved, another of its differences is that one processes the data with batch which refers to a process in which a set of data intervenes and that has a start and a end in time and in turn processes them with streaming which is continuously receiving and trying new information as they arrive without having an end in relation to the temporary section, on the contrary the other only processes the data with streaming.
---
## GitHub Commands
#### git init: Initialize the repository.
```javascript
Usuario@Santiago MINGW64 ~/Desktop/Proyecto (master)
$ git mv pagina.html index.html
Usuario@Santiago MINGW64 ~/Desktop/Proyecto (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    Bigdata.txt
        renamed:    pagina.html -> index.html

```
#### git status: Shows files created, modified from the repository.
```javascript
Usuario@Santiago MINGW64 ~/Desktop/Proyecto (master)
$ nano Bigdata.txt

Usuario@Santiago MINGW64 ~/Desktop/Proyecto (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Bigdata.txt

nothing added to commit but untracked files present (use "git add" to track)

```
#### git add: Add the file to the staging area.
```javascript
Usuario@Santiago MINGW64 ~/Desktop/Proyecto (master)
$ git add Bigdata.txt
warning: LF will be replaced by CRLF in bigdata.txt.
The file will have its original line endings in your working directory

```
#### git commit - m: Record the changes and add them to the repository.
```javascript
Usuario@Santiago MINGW64 ~/Desktop/Proyecto (master)
$ git commit
[master b77348c] First project
 1 file changed, 2 insertions(+)
 create mode 100644 Bigdata.txt

```

#### git log: Show the commits we have made in our repository.
```javascript
Usuario@Santiago MINGW64 ~/Desktop/Proyecto (master)
$ git log
commit b77348c433f7a5fae9e5cdd591e22870544f4549 (HEAD -> master)
Author: Santiago Molina <santy5555562@gmail.com>
Date:   Thu Jan 30 21:39:05 2020 -0600

    First project


```

#### git rm: Remove files from the staging area.
```javascript
Usuario@Santiago MINGW64 ~/Desktop/Proyecto (master)
$ git rm Bigdata.txt
rm 'Bigdata.txt'
Usuario@Santiago MINGW64 ~/Desktop/Proyecto (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    Bigdata.txt


```

#### git mv: It allows us to rename a file.
```javascript
Usuario@Santiago MINGW64 ~/Desktop/Proyecto (master)
$ git mv pagina.html index.html

Usuario@Santiago MINGW64 ~/Desktop/Proyecto (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    Bigdata.txt
        renamed:    pagina.html -> index.html

```

#### git diff: Shows the changes that have been made within the files.
```javascript
Usuario@Santiago MINGW64 ~/Desktop/Proyecto (master)
$ git diff
diff --git a/index.html b/index.html
index deeaa16..79bc175 100644
--- a/index.html
+++ b/index.html
@@ -4,7 +4,7 @@

     Bienvenidos a la UTM
 Hola mundo
-
+First project
 </body>

 </html>


```
#### git --amend: We can modify the most recent confirmation and even combine changes.
```javascript
Usuario@Santiago MINGW64 ~/Desktop/Proyecto (master)
$ git commit --amend
[master 2bbd870] HolaMundo
 Date: Thu Jan 30 21:39:05 2020 -0600
 1 file changed, 1 insertion(+)
 create mode 100644 index.html

```

#### git reset: Remove commits.
```javascript
Usuario@Santiago MINGW64 ~/Desktop/Proyecto (master)
$ git reset index.html
Unstaged changes after reset:
M       index.html

Usuario@Santiago MINGW64 ~/Desktop/Proyecto (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")


```
#### git checkout: Reverse the changes of the files, allow travel to different commits.
```javascript
Usuario@Santiago MINGW64 ~/Desktop/Proyecto (master)
$ git checkout
M       index.html
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

Usuario@Santiago MINGW64 ~/Desktop/Proyecto (master)
$ git checkout index.html
Updated 1 path from the index

}
```
_END_
