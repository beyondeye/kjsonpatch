[![Kotlin 1.1.1](https://img.shields.io/badge/Kotlin-1.1.1-blue.svg)](http://kotlinlang.org)
[![](https://jitpack.io/v/beyondeye/kjsonpatch.svg)](https://jitpack.io/#beyondeye/kjsonpatch)
[![Build Status](https://travis-ci.org/beyondeye/kjsonpatch.svg?branch=master)](https://travis-ci.org/beyondeye/kjsonpatch)
# Reduks: a port of Reduxjs for Kotlin+Android
Some notable features:

 - RxJava+RxAndroid support
 
 - Promise middleware based on kovenant promises (http://kovenant.komponents.nl/)
 
 - Thunk middleware
 
 - port of reselect library(https://github.com/reactjs/reselect)
 
 - A powerful logger middleware based on a port of https://github.com/evgenyrodionov/redux-logger, with the text
  formatting engine based on a heavily customized version of https://github.com/orhanobut/logger. 
  The reduks logger middleware allows to print Json diff of subsequent reduks states  thanks to a port to Kotlin of https://github.com/flipkart-incubator/zjsonpatch, with Jackson substituted with Gson and guava dependency removed

 - Support for easily combining multiple reduks modules
 
 - support for saving/restoring store state on activity onSaveInstanceState/onRestoreInstanceState

 - support for [Store Enhancers](https://github.com/reactjs/redux/blob/master/docs/Glossary.md#store-enhancer) (a generalization of middlewares),
  with helper functions to transform middlewares to store enhancers and combine them with other enhancers.

 - integration with a  [persistent collections library ](https://github.com/hrldcpr/pcollections) for better perfomance with complex states
 
 - Integration with an Event Bus implemented as Store enhancer
 

## License
Apache licence
