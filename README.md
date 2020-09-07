vim solution.sh
mkdir mydir
cd mydir
mkdir mydir2
cd mydir2
touch myfile
echo "hello bash" > myfile
cat myfile
cd ..
cp -r mydir2 mydir3
ls -a
find . | sort -r
:wq
chmod +x "solution.sh"
bash solution.sh 

