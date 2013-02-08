=====
Block Title Tooltip

-----
Block Title tooltip module creates a tooltip field in the Block configuration page. It works by creating new template variables in the $block object. then uses hook_preprocess_block to wrap a tooltip around the block->subject variable. There is a also a configuration parameter on a per block basis that disables the tooltip from rendering in the title.
