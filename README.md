[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=KERRCAM&hide=CMake,Makefile)](https://github.com/anuraghazra/github-readme-stats)

<!---[![KERRCAM's GitHub stats](https://github-readme-stats.vercel.app/api?username=KERRCAM&show_icons=true&theme=radical)](https://github.com/anuraghazra/github-readme-stats) 
 
 
 name: Waka Readme

on:
  workflow_dispatch: # for manual workflow trigger
  schedule:
    - cron: "0 0 * * *" # runs at every 12AM UTC

jobs:
  update-readme:
    name: WakaReadme DevMetrics
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          # following flags are required, only if this is not on
          # profile readme, remove the leading `#` to use them
          #GH_TOKEN: ${{ secrets.GH_TOKEN }}
          #REPOSITORY: <gh_username/gh_username>

<!--START_SECTION:waka-->
<!--END_SECTION:waka-->

