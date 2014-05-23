platform :ios, '5.0'
xcodeproj 'SDWebImage.xcodeproj'

target :default do
    link_with 'SDWebImage'
    pod 'iOS-WebP', '~> 0.3.1'
end

target :webp, :exclusive => true do
    link_with 'SDWebImage+WebP'
    pod 'iOS-WebP', '~> 0.3.1'
end
