desc 'Run tests'
task :test do
  command = "xcodebuild \
    -workspace THSegmentedPagerExample/THSegmentedPagerExample.xcworkspace \
    -scheme THSegmentedPagerExample \
    -sdk iphonesimulator -destination 'platform=iOS Simulator,name=iPhone 6,OS=latest' \
    test"
  system(command) or exit 1
end

task :default => :test