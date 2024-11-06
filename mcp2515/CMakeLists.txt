add_library(mcp2515
	mcp2515.cpp
)

target_include_directories(mcp2515 PUBLIC
	.
)

target_link_libraries(mcp2515 pico_stdlib hardware_spi hardware_dma)