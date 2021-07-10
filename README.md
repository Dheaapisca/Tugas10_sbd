## Nama   : Dhea Apisca
## NIM    : 311910755
## Kelas  : TI.19.B.2

# Tugas 10 Sistem Basis Data

### 1. Membuat Backup dan Recovery Data
![Backup and Recovery](https://user-images.githubusercontent.com/81975529/125177777-d371d300-e208-11eb-84e0-f83ed77fb226.PNG)
### 2. Membuat Backup dengan mysqldump
![mysql DUMP](https://user-images.githubusercontent.com/81975529/125177784-e1bfef00-e208-11eb-888c-9d612bb346b4.PNG)
### SCRIPT CRONJOB BACKUP OTOMATIS SELAMA 12 JAM
0 0 * * 7 mysqldump -u root -p78545 dheaapisca_311910775 > dheaapisca_311910775_backup.sql
