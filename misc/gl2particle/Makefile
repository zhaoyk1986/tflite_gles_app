include ../../Makefile.env

TARGET = gl2particle

SRCS = 
SRCS += main.c
SRCS += ../../common/assertgl.c
SRCS += ../../common/assertegl.c
SRCS += ../../common/util_egl.c
SRCS += ../../common/util_shader.c
SRCS += ../../common/util_matrix.c
SRCS += ../../common/util_debugstr.c
SRCS += ../../common/util_pmeter.c
SRCS += ../../common/util_texture.c
SRCS += ../../common/util_render2d.c
SRCS += ../../common/util_particle.c
SRCS += ../../common/winsys/$(WINSYS_SRC).c

OBJS =
OBJS += $(SRCS:%.c=./%.o)

INCLUDES += -I../../common/
INCLUDES += -I../../common/winsys/
INCLUDES += -I../../third_party/

CFLAGS   +=


LDFLAGS  +=
LIBS     +=

include ../../Makefile.include
