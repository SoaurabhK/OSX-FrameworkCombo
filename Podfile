workspace 'Final.xcworkspace'
use_frameworks!

target "First" do
    platform :osx, '10.7'
    project "First/First.xcodeproj"
    pod 'PubNub', '3.7.11'
    pod 'Typhoon'
    target 'FirstTests' do
        inherit! :search_paths
    end
end

target "Second" do
    platform :osx, '10.7'
    project "Second/Second.xcodeproj"
    pod 'SSZipArchive', '1.2'
    target 'SecondTests' do
        inherit! :search_paths
    end
end
