# PHP 7.1

RPM packages for RHEL / CentOS 7

### Installation

##### Install PHP 7.1

1. Install [**pkgs.cloud** release repository](https://github.com/pkgs-cloud/release)
2. `yum install php-7.1-release -y`
3. `yum install php -y`

##### List all available packages

```bash
yum --disablerepo="*" --enablerepo="pkgs.cloud-php-7.1" list available`
```

### Current build

#### PHP 7.1.3 packages

```
php                            7.1.3    
php-bcmath                     7.1.3    
php-cli                        7.1.3    
php-common                     7.1.3    
php-dba                        7.1.3    
php-dbg                        7.1.3    
php-devel                      7.1.3    
php-embedded                   7.1.3    
php-enchant                    7.1.3    
php-fpm                        7.1.3    
php-gd                         7.1.3    
php-gmp                        7.1.3    
php-imap                       7.1.3    
php-interbase                  7.1.3    
php-intl                       7.1.3    
php-json                       7.1.3    
php-ldap                       7.1.3    
php-litespeed                  7.1.3    
php-mbstring                   7.1.3    
php-mcrypt                     7.1.3    
php-mysqlnd                    7.1.3    
php-odbc                       7.1.3    
php-opcache                    7.1.3    
php-pdo                        7.1.3    
php-pdo-dblib                  7.1.3    
php-pear                       1.10.3 
php-pecl-apcu                  5.1.8
php-pecl-apcu-bc               1.0.3
php-pecl-apcu-devel            5.1.8
php-pecl-igbinary              2.0.1
php-pecl-igbinary-devel        2.0.1
php-pecl-imagick               3.4.3
php-pecl-imagick-devel         3.4.3
php-pecl-lzf                   1.6.5
php-pecl-memcached             3.0.3
php-pecl-msgpack               2.0.2
php-pecl-msgpack-devel         2.0.2
php-pecl-redis                 3.1.1
php-pecl-ssh2                  1.0  
php-pgsql                      7.1.3    
php-process                    7.1.3    
php-pspell                     7.1.3    
php-recode                     7.1.3    
php-snappy                     0.1.6
php-snmp                       7.1.3    
php-soap                       7.1.3    
php-tidy                       7.1.3    
php-xml                        7.1.3    
php-xmlrpc                     7.1.3
```

#### Additional packages

```
ImageMagick                    6.9.3.0  
ImageMagick-c++                6.9.3.0  
ImageMagick-c++-devel          6.9.3.0  
ImageMagick-devel              6.9.3.0  
ImageMagick-djvu               6.9.3.0  
ImageMagick-doc                6.9.3.0  
ImageMagick-libs               6.9.3.0  
ImageMagick-perl               6.9.3.0  
apcu-panel                     5.1.8
gd                             2.2.4    
gd-devel                       2.2.4    
gd-progs                       2.2.4    
jemalloc                       3.6.0
jemalloc-devel                 3.6.0
memcached                      1.4.36   
memcached-devel                1.4.36   
openssl                        1.0.2k
openssl-libs                   1.0.2k
openssl-devel                  1.0.2k 
openssl-perl                   1.0.2k 
openssl-static                 1.0.2k 
redis                          3.2.8
```

### Help with RPM packages

- [Open an issue](https://github.com/pkgs-cloud/release/issues)

---

##### DISCLAIMER

THIS SOFTWARE IS PROVIDED "AS IS" AND ANY EXPRESSED OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE REGENTS OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.