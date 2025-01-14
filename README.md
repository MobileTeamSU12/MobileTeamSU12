# Upload big file github
+ Step 1: Download and install Git on your pc. https://git-scm.com/downloads
+ Step 02: Then download and install GitLFS on your pc. Download link: https://git-lfs.github.com/
+ Step 03: Add file extensions big file cần upload
vd: `git lfs track "*.apk"` and `git lfs migrate import --include="*.apk"`
+ Step 04: Add file .gitattributes để lần sau sử dụng được tạo khi cmd trên, đã có file này thì ko cần add vào git `git add .gitattributes`
+ Step 05: add và commit sau đó push big file như bình thường. vd: 
```
git add file.psd
git commit -m "Add design file"
git push origin main
 ```
# Thống kê thông tin giữa 2 git commit
+ lệnh: `git diff --stat hash_comit1 hash_comit2`

# Mobimap_Install_mobimap
+ Dùng cài đặt mobiMap Hỗ trợ fix Bug
 - [https://mobileteamsu12.github.io/index](https://mobileteamsu12.github.io/index)
+ Dùng cài đặt mobiMap Hỗ trợ tester
 - [https://mobileteamsu12.github.io/test](https://mobileteamsu12.github.io/test)
+ Dùng cài đặt mobiMap Hỗ trợ UAT
 - [https://mobileteamsu12.github.io/uat](https://mobileteamsu12.github.io/uat)

+ Link Cài Đặt: `itms-services://?action=download-manifest&url=https://raw.githubusercontent.com/MobileTeamSU12/Mobimap_Install_mobimap/main/MobiMapVN_test.plist`
+ Link Web cài đặt: [http://htmlpreview.github.io/?https://raw.githubusercontent.com/MobileTeamSU12/Mobimap_Install_mobimap/main/MobiMap_Install_test.html](http://htmlpreview.github.io/?https://raw.githubusercontent.com/MobileTeamSU12/Mobimap_Install_mobimap/main/MobiMap_Install_test.html)

+ link: [https://mobileteamsu12.github.io/vn_ios_install/MobiMap_v3.32_production.ipa](https://mobileteamsu12.github.io/vn_ios_install/MobiMap_v3.32_production.ipa)

+ link: [https://mobileteamsu12.github.io/vn_ios_install/MobiMap_v3.33_CSOC.ipa](https://mobileteamsu12.github.io/vn_ios_install/MobiMap_v3.33_CSOC.ipa)
