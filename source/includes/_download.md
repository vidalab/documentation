# Download

Local builds are available for download. We have support for Windows and Mac.

## Windows

- <a href="https://s3-us-west-2.amazonaws.com/vida-public/windows/vida-windows-12-16-16.zip" target="_blank">Click here</a> to download Windows build
- Unzip file to a folder
- Open 2 command line windows and go to the unzipped folder
- In the first command line window, start database: start_db.bat
- In the second command line window, start vida server: start_vida.bat
- Open browser and go to application: http://localhost:8080

Note: Press Ctrl+C to exit batch processes. For vida server, after exit, you need to execute "cd .." to get outside of bundle directory.

## Mac

- <a href="https://s3-us-west-2.amazonaws.com/vida-public/mac/vida-mac-04-06-17.zip">Click here</a> to download Mac build
- Unzip file to a folder
- Open 2 command line windows and go to the unzipped folder
- In the first command line window, start database: start_db.sh
- In the second command line window, start vida server: start_vida.sh
- Open browser and go to application: http://localhost:8080

Note: Press Cmd+C to exit batch processes. For vida server, after exit, you need to execute "cd .." to get outside of bundle directory.

## Upgrade

When you upgrade your build, you need to retain the previous data directory.

- After you download, rename your previous build into data directory (e.g. vida_data.)
- Extract your new build.
- Go inside vida_data directory, start mongodb database. On mac, start_db.sh. On windows, start_db.bat.
- Go inside your new build directory, start Vida service. On mac, start_vida.sh, On windows, start_vida.bat.

WARNING: Be cautious of deleting any folder. You may not able to recover your data.