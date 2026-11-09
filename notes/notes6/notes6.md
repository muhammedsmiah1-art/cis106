# notes 6

## 1. mkdir
- definition: creates a new directory or multiple directories.
- usage/formula: mkdir [options] directory_name
- examples:
  mkdir new_folder
  mkdir -p parent_dir/sub_dir

## 2. touch
- definition: creates an empty file or updates the access and modification timestamps of an existing file.
- usage/formula: touch [options] file_name
- examples:
  touch file.txt
  touch file1.txt file2.txt

## 3. rm
- definition: removes (deletes) files or directories from the file system.
- usage/formula: rm [options] file_name
- examples:
  rm file.txt
  rm -r folder_name

## 4. cp
- definition: copies files or directories from a source location to a destination location.
- usage/formula: cp [options] source destination
- examples:
  cp file.txt backup.txt
  cp -r folder/ backup_folder/

## 5. mv
- definition: moves or renames files and directories.
- usage/formula: mv [options] source destination
- examples:
  mv old_name.txt new_name.txt
  mv file.txt /path/to/destination/
