# Tableau Server Client (Python)

* Due to tableau_server_client master v0.19.0 has error when get all tasks, So I want to fix some functions.

## PERSONAL SETUP

* folk code from master library
* reserve commit to v19
    * git checkout 1eeaca8709f548b73d7306a1251322c784e656c8
    * git checkout -b v19
    * git push origin v19
* merge v19 to master
    * git checkout master
    * git reset --hard v19
    * git push origin master --force

## CUSTOM FROM V19
* Update 2 file with v30 (f84d7d5302344f0a4ac369c501b122931ae7e79e)
    * schedule_item
    * interval_item
* interval_item
    * add 24 to VALID_INTERVALS = {0.25, 0.5, 1, 2, 4, 6, 8, 12, 24}