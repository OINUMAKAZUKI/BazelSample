java_binary(
  name = "main",
  srcs = glob(["**/*.java"]),
  main_class = "com.example.Main",
  deps = ["commons_lang"],
)
 
java_library(
  name="commons_lang",
  exports = [
    "@commons_lang//jar",
  ],
)