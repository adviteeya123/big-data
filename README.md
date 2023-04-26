# big-data
## Basic Linux commmands:
1. Create a file: touch file.txt
2. Delete a file: rm file.txt
3. How to see a content of from a file: cat file.txt
4. Create a folder: mkdir folder_name
5. To get inside a folder: cd folder_name
Practics atlease 20-30 linux commands which will be used in the hadoop system. e.g. jave point 
6. List of files and folders in a directory : ls


## Basic Hadoop commands
1. List of files and folers in hadoop file system : hdfs dfs -ls /
2. List of files with in a folder : hdfs dfs -ls /folder_name
## e.g. abc@c52b4b620c79:~/workspace$ hdfs dfs -ls /user_adi
# Found 1 items
# -rw-r--r--   1 abc supergroup         24 2023-04-27 00:52 /user_adi/abc.txt

4. Copy file from a local system to hdfs system : hdfs dfs -copyFromLocal ./folder_name/file_name /hadoop_folder_name 
## e.g. hdfs dfs -copyFromLocal abc.txt /user_adi

5. Create a directory in a hadoop system : hadoop fs -mkdir /user_adi   OR hadoop dfs -mkdir /user_adi1
