# DNS Performance Test

This is an arm32v6 unofficial docker image of https://github.com/cleanbrowsing/dnsperftest

Shell script to test the performance of the most popular DNS resolvers from your location.

Includes by default:
 * CloudFlare 1.1.1.1
 * Level3 4.2.2.1
 * Google 8.8.8.8
 * Quad9 9.9.9.9
 * Freenom 80.80.80.80
 * OpenDNS
 * Norton
 * CleanBrowsing
 * Yandex
 * AdGuard
 * Neustar
 * Comodo

# Usage

This image will run a DNS performance test using the most popular resolvers

Pull the image 
`docker run -it --rm airbornelamb/dnsperftest`


Run the test after it launches
`$ bash ./dnstest.sh |sort -k 22 -n`