source 'https://github.com/CocoaPods/Specs.git'

platform :ios, '9.0'
use_frameworks!

def library
    pod 'ICSMainFramework', :path => "./Library/ICSMainFramework/"
    pod 'KeychainAccess', :git => 'https://github.com/kishikawakatsumi/KeychainAccess.git'
end

def model
    #pod 'RealmSwift', :git => 'https://github.com/realm/realm-cocoa.git', :submodules => true
    pod 'Realm', git: 'https://github.com/realm/realm-cocoa.git', branch: 'master', submodules: true
    pod 'RealmSwift', git: 'https://github.com/realm/realm-cocoa.git', branch: 'master', submodules: true
end

target "iShadowsocksR" do
    pod 'Aspects', :path => "./Library/Aspects/"
    pod 'Cartography', :git => 'https://github.com/robb/Cartography.git'
    pod 'AsyncSwift', :git => 'https://github.com/duemunk/Async.git'
    pod 'SwiftColor', :git => 'https://github.com/icodesign/SwiftColor.git'
    pod 'Appirater', :git => 'https://github.com/arashpayan/appirater.git'
    pod 'MBProgressHUD', :git => 'https://github.com/matej/MBProgressHUD.git'
    pod 'ICDMaterialActivityIndicatorView', :git => 'https://github.com/icodesign/ICDMaterialActivityIndicatorView.git'
    pod 'ICSPullToRefresh', :git => 'https://github.com/icodesign/ICSPullToRefresh.Swift.git'
    #pod 'ISO8601DateFormatter', '~> 0.8'
    #pod 'Alamofire'
    pod 'Alamofire', :git => 'https://github.com/Alamofire/Alamofire.git', :branch => 'hotfix'
    pod 'ObjectMapper', :git => 'https://github.com/tristanhimmelman/ObjectMapper.git'
    pod 'PSOperations', :git => 'https://github.com/pluralsight/PSOperations.git'
    library
    model
end

target "TodayWidget" do
    pod 'Cartography', :git => 'https://github.com/robb/Cartography.git'
    pod 'SwiftColor', :git => 'https://github.com/icodesign/SwiftColor.git'
    library
    model
end

target "PotatsoLibrary" do
    library
    model
end

target "PotatsoModel" do
    model
end
