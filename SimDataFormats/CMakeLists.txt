add_subdirectory(GeneratorProducts)
add_subdirectory(PileupSummaryInfo)

add_custom_target(SimDataFormats_all)

add_dependencies(SimDataFormats_all
  SimDataFormatsGeneratorProducts
  SimDataFormatsPileupSummaryInfo
)
