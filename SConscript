from building import *

src = Glob('*.c')
src += Glob('src/*.c')
cwd = GetCurrentDir()
inc = [os.path.join(cwd, 'include')]

group = DefineGroup('RV_Backtrace', src, depend = [''], CPPPATH = inc)

Return('group')
