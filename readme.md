# Giles - Watcher extraordinaire..  
a continuous test runner for .NET applications. True to form, Giles will watch you kick ass, and let you know right away when you have made a mistake (intentionally or not).

# Useage:

giles.exe -s [path_to_solution] -t [path_to_test_assembly] -p [project_root_path]


# Command Line Help:

Giles Options

  s, SolutionPath        Required. Path to the sln file

  t, TestAssemblyPath    Required. Path to the test assembly dll

  p, ProjectRoot         Required. Path to the root of the project

  help                   Display this help screen.



# Interactive Console:

While in the interactive console, press ? for a list of options:

Interactive Console Options:
  ? = Display options  
  C = Clear the window  
  I = Show current configuration  
  R = Run build & tests now  
  B = Set Build Delay  
  Q = Quit  

For more information and requirement to run Giles, please visit the [wiki](https://github.com/codereflection/Giles/wiki)