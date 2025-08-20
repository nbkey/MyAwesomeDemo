# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

def base_pods
  # 从本地路径改为远程Git地址和Tag
  pod 'BaseModule', :git => 'git@github.com:YourCompany/BaseModule-iOS.git', :tag => '0.1.0'
end

target 'MyAwesomeDemo' do
  # Comment the next line if you don't want to use dynamic frameworks
  # use_frameworks!

  # Pods for MyAwesomeDemo
  pod 'Masonry'

  pod 'BaseModule', :path => './BaseModule'
end
