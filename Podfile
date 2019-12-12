# Uncomment the next line to define a global platform for your project
platform :ios, '11.0'

target 'LCSGroveTimeIO' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

# add the Firebase pod for Google Analytics
pod 'Firebase/Analytics'
# add pods for any other desired Firebase products
# https://firebase.google.com/docs/ios/setup#available-pods

  # Pods for GonativeIO
  pod 'OneSignal', '>= 2.11.2', '< 3.0'

  target 'LCSGroveTimeTests' do
    inherit! :search_paths
    # Pods for testing
  end

end

target 'OneSignalNotificationServiceExtension' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for OneSignalNotificationServiceExtension
  pod 'OneSignal', '>= 2.11.2', '< 3.0'
end
