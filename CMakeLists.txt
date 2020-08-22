cmake_minimum_required(VERSION 3.8)
project(stb)

add_library(stb 
	stb.h
  stb_c_lexer.h
  stb_conneced_componnents.h
  stb_divide.h
  stb_ds.h
  stb_dxt.h
  stb_easy_font.h
  stb_herringbone_wang_tile.h
  stb_image.h
  stb_image_resize.h
  stb_iamge_write.h
  stb_include.h
  stb_leakcheck.h
  stb_perlin.h
  stb_rect_pack.h
  stb_sprintf.h
  stb_textedit.h
  stb_tilemap_editor.h
  stb_truetype.h
  stb_vorbis.h
  stb_voxel_render.h
  stretchy_buffer.h)
target_include_directories(stb PUBLIC)
