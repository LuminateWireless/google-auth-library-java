package(default_visibility = ['//visibility:public'])

licenses(['notice'])

java_library(
  name = 'credentials',
  srcs = glob([
    'credentials/java/**/*.java'
  ])
)

java_library(
  name = 'oauth2_http',
  srcs = glob([
    'oauth2_http/java/**/*.java'
  ]),
  deps = [
    ':credentials',
    '//third_party/java/google-http-client',
    '//third_party/java/google-http-client:jackson2',
    '//third_party/java/guava',
  ],
)
