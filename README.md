# PHP 7.1

RPM packages for RHEL / CentOS 7

### Installation

##### Install PHP 7.1

1. Install [**pkgs.cloud** release repository](https://github.com/pkgs-cloud/release)
2. `yum install php-7.1-release -y`
3. `yum install php -y`

##### List all available packages

`yum --disablerepo="*" --enablerepo="pkgs.cloud-php-7.1" list available`

### Current build

#### PHP 7.1.3 packages

```
php.x86_64                            7.1.3-1.el7    
php-bcmath.x86_64                     7.1.3-1.el7    
php-cli.x86_64                        7.1.3-1.el7    
php-common.x86_64                     7.1.3-1.el7    
php-dba.x86_64                        7.1.3-1.el7    
php-dbg.x86_64                        7.1.3-1.el7    
php-devel.x86_64                      7.1.3-1.el7    
php-embedded.x86_64                   7.1.3-1.el7    
php-enchant.x86_64                    7.1.3-1.el7    
php-fpm.x86_64                        7.1.3-1.el7    
php-gd.x86_64                         7.1.3-1.el7    
php-gmp.x86_64                        7.1.3-1.el7    
php-imap.x86_64                       7.1.3-1.el7    
php-interbase.x86_64                  7.1.3-1.el7    
php-intl.x86_64                       7.1.3-1.el7    
php-json.x86_64                       7.1.3-1.el7    
php-ldap.x86_64                       7.1.3-1.el7    
php-litespeed.x86_64                  7.1.3-1.el7    
php-mbstring.x86_64                   7.1.3-1.el7    
php-mcrypt.x86_64                     7.1.3-1.el7    
php-mysqlnd.x86_64                    7.1.3-1.el7    
php-odbc.x86_64                       7.1.3-1.el7    
php-opcache.x86_64                    7.1.3-1.el7    
php-pdo.x86_64                        7.1.3-1.el7    
php-pdo-dblib.x86_64                  7.1.3-1.el7    
php-pear.noarch                       1:1.10.3-1.el7 
php-pecl-apcu.x86_64                  5.1.8-1.el7.7.1
php-pecl-apcu-bc.x86_64               1.0.3-6.el7.7.1
php-pecl-apcu-devel.x86_64            5.1.8-1.el7.7.1
php-pecl-igbinary.x86_64              2.0.1-1.el7.7.1
php-pecl-igbinary-devel.x86_64        2.0.1-1.el7.7.1
php-pecl-imagick.x86_64               3.4.3-1.el7.7.1
php-pecl-imagick-devel.x86_64         3.4.3-1.el7.7.1
php-pecl-lzf.x86_64                   1.6.5-3.el7.7.1
php-pecl-memcached.x86_64             3.0.3-1.el7.7.1
php-pecl-msgpack.x86_64               2.0.2-1.el7.7.1
php-pecl-msgpack-devel.x86_64         2.0.2-1.el7.7.1
php-pecl-redis.x86_64                 3.1.1-1.el7.7.1
php-pecl-ssh2.x86_64                  1.0-5.el7.7.1  
php-pgsql.x86_64                      7.1.3-1.el7    
php-process.x86_64                    7.1.3-1.el7    
php-pspell.x86_64                     7.1.3-1.el7    
php-recode.x86_64                     7.1.3-1.el7    
php-snappy.x86_64                     0.1.6-1.el7.7.1
php-snmp.x86_64                       7.1.3-1.el7    
php-soap.x86_64                       7.1.3-1.el7    
php-tidy.x86_64                       7.1.3-1.el7    
php-xml.x86_64                        7.1.3-1.el7    
php-xmlrpc.x86_64                     7.1.3-1.el7
```

#### Additional packages

```
ImageMagick.x86_64                    6.9.3.0-6.el7  
ImageMagick-c++.x86_64                6.9.3.0-6.el7  
ImageMagick-c++-devel.x86_64          6.9.3.0-6.el7  
ImageMagick-devel.x86_64              6.9.3.0-6.el7  
ImageMagick-djvu.x86_64               6.9.3.0-6.el7  
ImageMagick-doc.x86_64                6.9.3.0-6.el7  
ImageMagick-libs.x86_64               6.9.3.0-6.el7  
ImageMagick-perl.x86_64               6.9.3.0-6.el7  
apcu-panel.noarch                     5.1.8-1.el7.7.1
gd.x86_64                             2.2.4-3.el7    
gd-devel.x86_64                       2.2.4-3.el7    
gd-progs.x86_64                       2.2.4-3.el7    
jemalloc.x86_64                       3.6.0-1.el7
jemalloc-devel.x86_64                 3.6.0-1.el7
memcached.x86_64                      1.4.36-1.el7   
memcached-devel.x86_64                1.4.36-1.el7   
openssl.x86_64                        1:1.0.2k-1.el7
openssl-libs.x86_64                   1:1.0.2k-1.el7
openssl-devel.x86_64                  1:1.0.2k-1.el7 
openssl-perl.x86_64                   1:1.0.2k-1.el7 
openssl-static.x86_64                 1:1.0.2k-1.el7 
redis.x86_64                          3.2.8-1.el7
```

### Help with RPM packages

- [Open an issue](https://github.com/pkgs-cloud/release/issues)

---

##### DISCLAIMER

THIS SOFTWARE IS PROVIDED "AS IS" AND ANY EXPRESSED OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE REGENTS OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.