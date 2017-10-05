project 'Tests/FMDBMigrationManagerTests'
workspace 'FMDBMigrationManager'

def import_pods
  pod 'Expecta', '~> 0.3.0'
  pod 'FMDB/standard'
  pod 'FMDBMigrationManager', :path => '.'
end

target 'iOS Tests' do
  project 'Tests/FMDBMigrationManagerTests.xcodeproj'
  platform :ios, '7.0'
  import_pods
end

target 'OS X Tests' do
  project 'Tests/FMDBMigrationManagerTests.xcodeproj'
  platform :osx, '10.9'
  import_pods
end
