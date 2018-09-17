# tenfourfox-macports
portfiles to build tenfourfox using MacPorts

To use this repository, first clone it to your local drive
```
cd /Users/Shared
git clone https://github.com/kencu/tenfourfox-macports.git
```
And then tell your installation of MacPorts to use it as an additional repository. We will place this after the main MacPorts repository, so as not to interfere with any ports in the main repository.

assuming you installed MacPorts into /opt/local

```
sudo vi /opt/local/etc/macports/sources.conf
```
and add the following source to the end of the file
```
file:///Users/Shared/tenfourfox-macports
```
