iOS-Project-Creator
===================

Clones the default Cloudspace iOS project and modifies it to have the desired naming scheme.


**Prerequisites**
 - gem install cocoapods
 - pod repo add cloudspace git@github.com:cloudspace/Cloudspace-iOS-PodSpecs

**One line usage**
 - ruby <( curl https://raw.github.com/cloudspace/iOS-Project-Creator/master/create.rb ) ProjectName FilePrefix


Since this is a cocoapods project open the xcworkspace file not the xcproject file.
