pip3 install virtualenv
python3 -m venv .venv
pip3 freeze > requirements.txt
pip3 install -r requirements.txt
source .venv/bin/activate

pip install numpy
pip install opencv-python
pip install pillow




echo "# image_editor" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://repo
git push -u origin main