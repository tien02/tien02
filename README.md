- 👋 Hi, I’m @tien02.
- 👀 I’m interested in Data Science, Artificial Intelligent
- 🌱 I’m learning Machine Learning, Deep Learning, especially Computer Vision area.
- 💞️ I’m currently studing at University of Information and Technology (UIT) at Ho Chi Minh City.
- 📫 Contact me at email address 20520800@gm.uit.edu.vn.

<!--START_SECTION:badges-->
name: Update badges

on:
  schedule:
    # Runs at 2am UTC
    - cron: "0 2 * * *"
jobs:
  update-readme:
    name: Update Readme with badges
    runs-on: ubuntu-latest
    steps:
      - name: Badges - Readme
        uses: pemtajo/badge-readme@main
        with:       
          CREDLY_USER: <Tiến Đặng> # optional, but default will use the same from github
<!--END_SECTION:badges-->

<!---
tien02/tien02 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
