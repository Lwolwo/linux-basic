#Linux练习
```
mkdir cli-practice 
cd cli-practice
touch readme.md
echo 'Hi there, this is a readme file.' >> readme.md
echo 'This is the second line of the readme file.' >> readme.md
mv readme.md readme.txt
mkdir document
mv readme.txt ./document
cd document
mv readme.txt introduction.txt
cp introduction.txt readme.txt
echo 'The quick brown fox jumps over a lazy dog' > readme.txt
cd ..
cp -r document docus
rm -rf document
mkdir -p parent/child/docs
cp ./docus/introduction.txt ./parent/child/docs
```