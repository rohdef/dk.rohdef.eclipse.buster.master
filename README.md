# Buster plugin maven master

This is just to combine the parts into something for maven, to build it 
install maven 3 and run

    git clone git://github.com/rohdef/dk.rohdef.eclipse.buster.git
    git clone git://github.com/rohdef/dk.rohdef.eclipse.buster.feature.git
    git clone git://github.com/rohdef/dk.rohdef.eclipse.buster.test.git
    git clone git://github.com/rohdef/dk.rohdef.eclipse.buster.master.git
    cd dk.rohdef.eclipse.buster.master
    mvn compile

## Links to other repositories
[dk.rohdef.eclipse.buster - The actual plugin](https://github.com/rohdef/dk.rohdef.eclipse.buster)
[dk.rohdef.eclipse.buster.feature - Setup for eclipse updata manager](https://github.com/rohdef/dk.rohdef.eclipse.buster.feature)
[dk.rohdef.eclipse.buster.test - Tests for the plugin](https://github.com/rohdef/dk.rohdef.eclipse.buster.test)
[dk.rohdef.eclipse.buster.master - The Maven master project, just used for the build system](https://github.com/rohdef/dk.rohdef.eclipse.buster.master)
