# fetch
actually, meowfetch  
because meow was hidden somewhere

## functionality
- outputs basic system info
  - hostname & kernel version, cpu + cores + freq, ram used & total, package count

## to do
- [ ] improve CPU model parsing for AMD/ARM/Apple chips (`cpu_info`)
- [ ] extend package manager detection (`pkg_count`)
- [ ] add fallback when `/proc` isn't available (e.g., inside containers)
- [ ] maybe: ASCII variants/themes?
