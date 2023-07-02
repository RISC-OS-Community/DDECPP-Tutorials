# Makefile for example a generic app written in DDE C++ (CFront)

COMPONENT = TestPrivate
OBJS      = Main SomeClass

# This bit of magic tells the shared makefiles to change the link rules it
# uses to suit the C++ system
LINK_TYPE = C++

include CApp
DBG_LIBS= C:C++Lib.o.c++lib C:DebugLib.o.DebugLib C:remotedb.o.remotedb C:DDTLib.o.DDTLib CLIB:o.stubs C:Trace.o.Trace C:PDebug.o.PDebug C:ModMalloc.o.ModMalloc


# Dynamic dependencies:
