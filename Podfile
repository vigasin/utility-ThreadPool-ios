Pod::Spec.new do |s|
  s.name               = "utility-ThreadPool-ios"
  s.version            = '1.0'
  s.summary            = 'The thread pool and URL dispatch library'
  s.homepage           = 'https://github.com/vigasin/utility-ThreadPool-ios'
  s.authors            = 'Some guys'
  s.license            = 'Apache License, Version 2.0'
  s.source             = { :git => 'https://github.com/vigasin/utility-ThreadPool-ios.git', :commit => 'b755578373925b9c36ba81e0c9706bb1ff5bcd21' }
  s.source_files       = 'SocketRocket/*.{h,m,c}'
  s.requires_arc       = true
  s.ios.frameworks     = %w{CFNetwork Security}
  s.osx.frameworks     = %w{CoreServices Security}
  s.osx.compiler_flags = '-Wno-format'
  s.libraries          = "icucore"
end
