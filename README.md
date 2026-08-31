name: Github-Auto-Follow-Unfollow-View-User-List

on:
  workflow_dispatch:
  schedule:
    - cron: '0 */8 * * 1-5'

jobs:
  auto-update:
    runs-on: ubuntu-latest
    steps:
      - name: Github-Auto-Follow-Unfollow-View-User-List
        uses: Huniko519/Github-Auto-Follow-Unfollow-View-User-List@main
        with:
          token: ${{ secrets.TOKEN }}
          repository: ${{ github.repository }}
          isReadmeUpdate: true
          isEnableFollow: true
          isEnableUnfollow: true
          safeUserList: 'Babi1205,Huniko-Team'


<div align="center">

![Visitor Count](https://hits.sh/thehotelkeeper.github.io.svg?label=🖤&color=777777)



<div align="center">


<img width="540" height="547" alt="image" src="https://github.com/user-attachments/assets/71a76f66-e68c-4774-9b5e-21fbe13f2580" />
