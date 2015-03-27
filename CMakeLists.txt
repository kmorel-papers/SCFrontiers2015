cmake_minimum_required(VERSION 3.0)

project(SCFrontiers2015 NONE)

include(UseLATEX.cmake)

set(images
  images/ExampleMesh.pdf
  images/StreamCompaction.pdf
  images/ReverseLookup.pdf
  images/rm650_teaser.png
  )

add_latex_document(SCFrontiers2015.tex
  BIBFILES SCFrontiers2015.bib
  IMAGES ${images}
  )
