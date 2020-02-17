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
# Tarea1
---
## Life cycle of data analysis

### Business Understanding:
#### This initial phase focuses on understanding the objectives and requirements of the project from a business perspective, and then converting this knowledge into a definition of data mining problem. A preliminary plan is designed to achieve the objectives. A decision model can be used, especially one created using the decision model and the notation standard.

### Understanding the data:
#### The data comprehension phase begins with an initial collection of data and continues with activities to familiarize yourself with the data, identify data quality problems, discover the first ideas about the data or detect interesting subsets to form hypotheses to hide information. 

### Data Preparation:
####  The data preparation phase covers all activities to build the final data set (data that will be incorporated into the modeling tools) from the initial raw data. Data preparation tasks are likely to be performed several times and not in the prescribed order. Tasks include the selection of tables, records and attributes, as well as the transformation and cleaning of data for modeling tools.

### Modeling:
#### In this phase, several modeling techniques are selected and applied and their parameters are calibrated to optimal values. Generally, there are several techniques for the same type of data mining problem. Some techniques have specific requirements on the form of the data. Therefore, it is often required to go back to the data preparation phase.

### Evaluation:
#### At this stage of the project, you have created a model (or models) that seems to have high quality, from the perspective of data analysis. Before proceeding with the final deployment of the model, it is important to evaluate it thoroughly and review the steps taken to build the model, to ensure that it adequately achieves business objectives. A key objective is to determine if there is an important commercial problem that has not been sufficiently considered. At the end of this phase, a decision must be reached on the use of data mining results.

### Implementation:
#### Model creation is generally not the end of the project. Even if the purpose of the model is to increase the knowledge of the data, the knowledge acquired should be organized and presented in a way that is useful to the customer. Depending on the requirements, the implementation phase can be as simple as generating a report or as complex as implementing a repeatable data score (for example, segment assignment) or a data mining process.
---
## Types of statistics

### Inferential statistics:
#### Inferential statistics are produced through complex mathematical calculations that allow scientists to infer trends over a larger population based on the study of a sample taken from it. Scientists use inferential statistics to examine the relationships between variables within a sample and then make generalizations or predictions about how those variables will relate to a larger population.

### Descriptive statistics:
#### Descriptive statistics is the type of statistics that probably arises in the minds of most people when they hear the word "statistics." In this branch of statistics, the objective is to describe. Numerical measurements are used to report the characteristics of a data set. There are a number of elements that belong to this part of the statistics.

### APPLIED:
####  It is made up of the two kinds of previous statistics. Its objective is to deduce results on a universe, from a given sample. This type of statistics can be applied in any area that does not belong to it, such as history, psychology, etc.

### MATHEMATICAL STATISTICS:
#### It refers to the use of statistics but from a formal point of view, through the use of different branches of mathematics and probability theory. Its use is necessary because the data handled by mathematical statistics are random and uncertain.
---
## EDA
#### Exploratory Data Analysis (EDA) is an approach / philosophy for data analysis that employs a variety of (mainly graphic) techniques to:
1. Maximize knowledge of a data set;
2. Discover the underlying structure;
3. Extract important variables;
4. Detect outliers and anomalies;
5. Prove underlying assumptions;
6. Develop parsimonious models; Y
7. Determine the optimal factor setting.

### Techniques:
#### Most EDA techniques are graphic in nature with some quantitative techniques. The reason for the great dependence on graphics is that, by their very nature, the main role of EDA is to explore openly, and graphics give analysts an incomparable power to do so, attract data to reveal their structural secrets and be always ready. to get a new, often unsuspected, view of the data. In combination with the natural pattern recognition capabilities we all possess, the graphics provide, of course, unmatched power to carry it out.
---
## ETL
#### ETL is short for extract, transform, load, three database functions that are combined into one tool to pull data out of one database and place it into another database.
#### Extract is the process of reading data from a database. In this stage, the data is collected, often from multiple and different types of sources.

#### Transform is the process of converting the extracted data from its previous form into the form it needs to be in so that it can be placed into another database. Transformation occurs by using rules or lookup tables or by combining the data with other data.

#### Load is the process of writing the data into the target database.

### How ETL Works:
#### Data from one or more sources is extracted and then copied to the data warehouse. When dealing with large volumes of data and multiple source systems, the data is consolidated. ETL is used to migrate data from one database to another, and is often the specific process required to load data to and from data marts and data warehouses, but is a process that is also used to to large convert (transform) databases from one format or type to another.
---
## Data flow diagram
#### A data flow diagram (DFD) illustrates the flow and transformation of data for a particular business process. It is a visual representation of how data flows through a system, so you can clearly see where the data comes from, where it goes and how it is stored.

### Elements of a data flow diagram:
#### The processes are a circle or a square with a horizontal line along the top. A process is a business activity in which data manipulation and transformation occurs. Something happens to the data during a process.

#### The arrows represent the way data flows. Use the type of data that moves through the system as the name for the arrow.

#### An external entity is shown as a square. An external entity can be a person, a system or an application. It is where the data starts or ends.

#### The data stores are rectangles (sometimes with a vertical line in the symbol) and show where the required or produced data is stored in relation to the process.


_END_

## Team
### Jesús Israel Cua Uicab
### Santiago Daniel Molina Navarrete
### Roger Argaez Cocom
### Joel Chan Méndez
