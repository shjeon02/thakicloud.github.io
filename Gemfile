source "https://rubygems.org"

# Security fix for CVE-2025-27221 bypass (credential exposure via URI + operator)
gem "uri", ">= 1.0.4"

# Security fix for CVE-2025-58767 (DoS vulnerability in REXML XML parsing)
gem "rexml", ">= 3.4.2"

# Security fix for CVE-2026-35611 (addressable credential exposure)
gem "addressable", ">= 2.9.0"

# Security fix for CVE-2026-33637, CVE-2026-25765 (faraday request smuggling / auth)
gem "faraday", ">= 2.14.1"

gem "jekyll", "~> 4.3"
gem "minimal-mistakes-jekyll", "~> 4.27"
gem "faraday-retry", "~> 2.3"
gem 'tzinfo'
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :jekyll_plugins do
  gem "jekyll-seo-tag"
end
