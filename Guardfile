  guard :rspec, :all_on_start => false do
    watch(%r{^spec/(.*)_spec.rb$})
    watch(%r{^lib/(.+).rb$})         { |m| "spec/lib/#{m[1]}_spec.rb" }
    watch(%r{^spec/spec_helper.rb$}) { 'rspec' }

    watch(%r{^app/(models|mailers|helpers)/(.+).rb$}) { |m|
      "test/#{m[1]}/#{m[2]}_spec.rb"
    }
    watch(%r{^app/controllers/api/(.+)_controller.rb$}) { |m| "spec/requests/>
  end
