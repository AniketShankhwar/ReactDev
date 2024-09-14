# React Learning ⚡

# Parcel
- Dev Build
- Local Server
- HMR = Hot Module Replacement
- File Watching Algorithm - written in C++
- Caching -  Faster Builds
- Image Optimization
- Minification
- Bundling
- Compress
- Consistent Hashing
- Code Splitting
- COde Splitting
- Differential Bundling - support older browsers
- Diagnostic
- Error Handling
- HTTPs
- Tree Shaking - remove unused code
- Different dev and production bundles

# In Package.json
  "dependencies": {
    "react": "^18.3.1",       
    "react-dom": "^18.3.1"    
  }                           
  - Using a caret (^) sign means that we can accept minor releases and patch releases, but not a major release when updating our package. e.g. 18.3.1 => 18.3.2
  - Using a tilde (~) sign before our version number means that we can accept only a patch release when updating our package. e.g. 18.3.1 => 18.4.1
  - Using an asterisk (*) means “accept all releases”, but this is not advisable as it will accept major releases and may break our code. e.g. 18.3.1 => 20.4.1
