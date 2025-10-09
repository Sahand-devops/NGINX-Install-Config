### Innan jag började med att ladda ned NGINX så uppdaterade jag ubuntu pakethanteraren först.
```
sudo apt update

sudo apt install nginx -y

``` 
### Jag verifierade att NGINX körs genom att kolla statusen.
``` 
systemctl status nginx
```

#### Jag redigerad index.html filen i Github och bytte ut texten "Username" mot mitt GitHub-användarnamn. Därefter ladda jag hem filen till min windows dator. 

#### För att NGINX skulle använda min index.html fil som startsida kopierade jag den filen till webbserverns katalog '/var/www/html/'.

```
sudo cp /mnt/c/Users/Sahan/nackademin/l11-nginx-d4-Sahand-devops/index.html /var/www/html/index.html
```

### Sedan gick jag in på http://localhost i min webbläsare och kollade att det fungerade.

### För att ta reda på viktiga loggfiler för NGINX så kollade jag på:

``` 
ls /var/log/nginx
 --> access.log
 --> error.log
``` 

#### access.log - loggar alla HHTP-förfrågningar. 
#### error.log - loggar fel och varningar.

