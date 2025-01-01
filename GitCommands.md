# **English Version:**

# Git Commands

## General Configuration
- `git -v` (or `git --version`): Display the installed Git version.
- `git config --global user.name "your-username"`: Set the global username for Git commits.
- `git config --global user.email "your-email@example.com"`: Set the global email for Git commits.

## Initializing and Adding Changes
- `git init`: Initialize a new Git repository in the current directory.
- `git add`: Stage specific files for the next commit.
- `git add .`: Stage all changes (new, modified, and deleted files) for the next commit.

## Committing Changes
- `git commit -m "Message"`: Commit staged changes with a descriptive message.

## Viewing History
- `git log`: View the commit history with detailed information.
- `git log --oneline`: View the commit history in a concise format.

## Branching and Switching
- `git branch`: List all branches in the repository.
- `git branch name-branch`: Create a new branch with the specified name.
- `git switch name-branch`: Switch to an existing branch.
- `git checkout master`: Switch to the master branch.
- `git checkout 1a2b3c4`: Check out a specific commit by its hash.

## Merging and Syncing
- `git merge name-branch`: Merge the specified branch into the current branch.

## Remote Repositories
- `git remote add origin https://github.com/username/name-repo.git`: Add a remote repository with the name "origin".
- `git remote`: List all remote repositories.
- `git clone https://github.com/username/name-repo.git`: Clone an existing repository to your local machine.

## Pushing and Pulling
- `git push -u origin master`: Push the master branch to the remote repository and set upstream tracking.
- `git push`: Push committed changes to the current branch's remote tracking branch.
- `git pull origin master`: Fetch and merge changes from the master branch of the remote repository.
- `git push --set-upstream origin name-branch`: Push a branch to the remote repository and set upstream tracking.

---

<div dir="rtl">

# **نسخه فارسی:** 

# دستورات Git

## پیکربندی عمومی
- `git -v` (or `git --version`): نمایش نسخه Git نصب شده.
- `git config --global user.name "your-username"`: تنظیم نام کاربری جهانی برای commit‌ها.
- `git config --global user.email "your-email@example.com"`: تنظیم ایمیل جهانی برای commit‌ها.

## راه‌اندازی و اضافه کردن تغییرات
- `git init`: راه‌اندازی یک مخزن Git جدید در دایرکتوری فعلی.
- `git add`: مرحله‌بندی فایل‌های خاص برای commit بعدی.
- `git add .`: مرحله‌بندی تمام تغییرات (فایل‌های جدید، تغییر داده شده و حذف شده) برای commit بعدی.

## انجام تغییرات
- `git commit -m "Message"`: ثبت تغییرات مرحله‌بندی شده با یک پیام توضیحی.

## مشاهده تاریخچه
- `git log`: مشاهده تاریخچه commit‌ها با اطلاعات دقیق.
- `git log --oneline`: مشاهده تاریخچه commit‌ها در یک قالب خلاصه.

## شاخه‌ها و تغییر بین آنها
- `git branch`: فهرست تمام شاخه‌های موجود در مخزن.
- `git branch name-branch`: ایجاد یک شاخه جدید با نام مشخص شده.
- `git switch name-branch`: تغییر به یک شاخه موجود.
- `git checkout master`: تغییر به شاخه اصلی (master).
- `git checkout 1a2b3c4`: بررسی یک commit خاص با استفاده از هش آن.

## ادغام و همگام‌سازی
- `git merge name-branch`: ادغام شاخه مشخص شده با شاخه فعلی.

## مخازن راه دور
- `git remote add origin https://github.com/username/name-repo.git`: اضافه کردن یک مخزن راه دور با نام "origin".
- `git remote`: فهرست تمام مخازن راه دور.
- `git clone https://github.com/username/name-repo.git`: کلون کردن یک مخزن موجود به دستگاه محلی.

## ارسال و دریافت تغییرات
- `git push -u origin master`: ارسال شاخه master به مخزن راه دور و تنظیم ردیابی بالادستی.
- `git push`: ارسال تغییرات متعهد شده به شاخه ردیابی راه دور فعلی.
- `git pull origin master`: دریافت و ادغام تغییرات از شاخه master مخزن راه دور.
- `git push --set-upstream origin name-branch`: ارسال یک شاخه به مخزن راه دور و تنظیم ردیابی بالادستی.

</div>
```