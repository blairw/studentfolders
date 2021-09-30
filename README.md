# studentfolders

```zsh
for d in */ ; do
    cd "$d"
    mkdir "ASMT_MIDTERM"
    cd "ASMT_MIDTERM"
    echo "Please upload your Midterm work here" > "README.txt"
    cd ..
    mkdir "ASMT_FINAL_EXAM"
    cd "ASMT_FINAL_EXAM"
    echo "Please upload your Final Exam work here" > "README.txt"
    cd ..
    cd ..
done
```
