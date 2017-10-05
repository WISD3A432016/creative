# creative
git 版本控制練習

由於git checkout --{file} ，用於單一檔案回復，且在尚未Commit前，
所以看不到修改回來的檔案，
所以先將原先修改的index.html檔案commit出去後，
再用revert指令來還原commit 記錄 -> git revert {commit號碼}
這樣就能在branches看到修改前和修改後記錄
