~/.config/nvim/lua/plugins/codam-header-python.lua 
```
return {
	'grilled-pasta/42-header-python.nvim',
	name = '42pyheader',
	lazy = false,
	opts = {
		default_map = true,
		user = "...",
		mail = "..."
	},
	config = function(_, opts)
		require('42pyheader').setup(opts)
	end,
}
```
