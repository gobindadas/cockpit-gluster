# cockpit-gluster [work in progress]
A GD2 based dashboard for gluster management

## Install Dependencies
```
sudo yum install -y cockpit npm
```

## Install node modules
```
npm install
```

## Compile Javascript
```
npx --no-install webpack
```

## Build an rpm
```
make rpm
```
## Install to a remote host running GD2
```
./scripts/rem_install.bash hostname
```

## Screenshots
![Dashboard Image](/screenshots/dashboard.png?raw=true "Dashboard")
![Volume Modal Image](/screenshots/volume_modal.png?raw=true "Volume Modal")

## Installing GD2

GD2 developement guide: https://github.com/gluster/glusterd2/blob/master/doc/development-guide.md

GD2 quickstart guide: https://github.com/gluster/glusterd2/blob/master/doc/quick-start-user-guide.md

With my scripts (on CentOS VMs): https://github.com/rohantmp/gd2-testing