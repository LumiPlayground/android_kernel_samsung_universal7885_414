# SPDX-License-Identifier: GPL-2.0
dtb-y += exynos/exynos7885.dtb
dtb-y += exynos/exynos7885_4.4_bl.dtb
dtb-y += exynos/exynos7885-jackpotlte_eur_open_07.dtb
dtbo-y += samsung/exynos7884B-a10eu_jpn_dcm_01.dtbo
dtbo-y += samsung/exynos7884B-a10eu_jpn_dcm_00.dtbo

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
