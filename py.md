Settings的User是VScode的全域設定:會套用到所有地方，不管從哪邊開啟檔案跟資料夾
          Workspace:只改目前的資料夾的個人化設定(會多了json檔)

安裝py除錯:
          在terminal輸入指令(安裝除錯程式): pip install pylint
          在settings.json加入(開啟除錯功能):"python.linting.enabled": true,
                              "python.linting.pylintEnabled":true
                              
建置VS code環境:打開CMD
python -V:查看目前版本
pip3 list:目前Python環境下，安裝了哪些套件或是framework

