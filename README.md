# Learning Clojure

+ https://thoughtbot.com/blog/tips-for-clojure-beginners

## Install Clojure

### install openjdk
``` sh
sudo apt install openjdk-17-jdk
```

### Install lein

+ https://leiningen.org/#install
``` sh
wget https://raw.githubusercontent.com/technomancy/leiningen/stable/bin/lein ~/bin/
lein
```

## Start with koans

### Cloan koans repo inside ours and remove .git

``` sh
git clone git://github.com/functional-koans/clojure-koans.git ~/Comp/Clojure/clojure-koans
sudo rm -rf ~/Comp/Clojure/clojure-koans/.git
```

### Launch koans

``` sh
cd ~/Comp/Clojure/clojure-koans
lein koan run
```
