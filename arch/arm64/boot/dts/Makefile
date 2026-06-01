# SPDX-License-Identifier: GPL-2.0

# Exynos 3830
dtbo-y += exynos/exynos3830-universal3830_r01.dtbo
dtbo-y += exynos/exynos3830-universal3830_r03.dtbo
dtbo-y += exynos/exynos3830-universal3830_r15.dtbo
dtb-y += exynos/exynos5433-tm2e.dtb
dtb-y += exynos/exynos5433-tm2.dtb
dtbo-y += exynos/exynos3830-universal3830_r00.dtbo
dtb-y += exynos/exynos7-espresso.dtb
dtbo-y += exynos/exynos3830-universal3830_r04.dtbo
dtb-y += exynos/exynos3830.dtb
dtbo-y += exynos/exynos3830-universal3830_r02.dtbo

# Samsung Galaxy A12s
dtbo-y += samsung/a12s/a12s_eur_open_w00_r00.dtbo
dtbo-y += samsung/a12s/a12s_eur_open_w00_r01.dtbo

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
