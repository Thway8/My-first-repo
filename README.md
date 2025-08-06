# My-first-repo
အခုမှစတင်အသုံးပြုမဲ့သူတို့အတွက် အတူတူလေ့လာနိုင်ပါတယ်
# 1. Terminal မှာ project folder ထဲဝင်
cd my-project-folder/

# 2. Git Initialize
git init

# 3. File တွေကို Git မှာ Add
git add .

# 4. First Commit
git commit -m "Initial commit"

# 5. Remote Repo ကိုချိတ် (GitHub မှာပြုလုပ်ထားတဲ့ repo URL ကိုသုံးပါ)
git remote add origin https://github.com/USERNAME/REPO_NAME.git

# 6. Push လုပ်ခြင်း
git push -u origin master
# သို့မဟုတ် GitHub သုံးတဲ့ default branch ဖြစ်တဲ့ main ကို:
git push -u origin main
