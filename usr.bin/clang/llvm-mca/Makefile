
PROG_CXX=	llvm-mca

SRCDIR=		llvm/tools/llvm-mca
SRCS+=		CodeRegion.cpp
SRCS+=		CodeRegionGenerator.cpp
SRCS+=		PipelinePrinter.cpp
SRCS+=		Views/BottleneckAnalysis.cpp
SRCS+=		Views/DispatchStatistics.cpp
SRCS+=		Views/InstructionInfoView.cpp
SRCS+=		Views/InstructionView.cpp
SRCS+=		Views/RegisterFileStatistics.cpp
SRCS+=		Views/ResourcePressureView.cpp
SRCS+=		Views/RetireControlUnitStatistics.cpp
SRCS+=		Views/SchedulerStatistics.cpp
SRCS+=		Views/SummaryView.cpp
SRCS+=		Views/TimelineView.cpp
SRCS+=		llvm-mca.cpp

CFLAGS+=	-I${LLVM_BASE}/${SRCDIR}

LIBADD+=	z

.include "../llvm.prog.mk"
