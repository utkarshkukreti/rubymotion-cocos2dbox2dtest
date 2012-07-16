# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project'
require 'motion-cocoapods'

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'Cocos2DBox2DTest'

  app.pods do
    dependency 'cocos2d'
    dependency 'box2d'
  end

  app.vendor_project('vendor/GBox2D', :static)
end
