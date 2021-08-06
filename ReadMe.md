## Duck
### Duck Duck 

## To Compile on macOS
```
# create Python 3 virtual environment
python3 -m venv venv

# activate the virtual environment
source venv/bin/activate

# install the dependencies from requirements.txt
pip install -r requirements.txt

# compile the app using PyInstaller
pyinstaller --clean --noconfirm app.spec

# now you may find the Duck.app file in ./dist/
```

## Current Status 

### Already Done 
    1. 有一条狗
    ~~2. 能拖着跑~~
    ~~3. 跑的时候能动~~
    2. 可以拖动
    3. 双击开始/停止跑动
    4. 右键打开可以调教狗子（talk功能待实现）
    5. 加入系统托盘菜单（内容同4）

### To Be Done
    1. 狗太笨，啥也不会
        e.g 自己走路？ 
            定时提醒？ 。。。 
    2. 狗不会说话 [Doge]
