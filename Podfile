# Uncomment the next line to define a global platform for your project
 platform :ios, '17.0'

project 'Powerup.xcodeproj'

target 'Powerup' do
  
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!
  
  # Pods for Playtube
  pod 'IQKeyboardManagerSwift'
  pod 'Alamofire'
  pod 'SwiftyBeaver'
  pod 'JGProgressHUD'
  pod 'Toast-Swift', '~> 4.0.0'
  pod "AsyncSwift"
  pod 'R.swift'
  pod 'SDWebImage', '~> 4.0'
  pod 'DropDown'
  pod 'GoogleSignIn', '5.0.0'
  pod 'FBSDKLoginKit'
  pod 'OneSignal', '>= 2.6.2', '< 3.0'
  pod 'UIView-Shimmer'
  pod 'Google-Mobile-Ads-SDK'
  pod 'SwiftEventBus', :tag => '3.0.0', :git => 'https://github.com/cesarferreira/SwiftEventBus.git'
  pod 'FittedSheets'
  pod 'ActiveLabel'
  pod 'Braintree'
  pod 'AgoraRtcEngine_iOS'
  pod 'HCVimeoVideoExtractor'
  pod "youtube-ios-player-helper"
  pod 'razorpay-pod'
  pod 'CashfreePG'
  pod 'SwiftSoup'
  pod 'Stripe'
  pod 'Cosmos'
  
end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['ONLY_ACTIVE_ARCH'] = 'YES'
      config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '13.0'
    end
  end
end
