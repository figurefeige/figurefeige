- 👋 Hi, I’m @figurefeige
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
figurefeige/figurefeige is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->Collecting pandas
  Using cached pandas-2.2.2.tar.gz (4.4 MB)
  Installing build dependencies ... error
  error: subprocess-exited-with-error
  
  × pip subprocess to install build dependencies did not run successfully.
  │ exit code: 1
  ╰─> [56 lines of output]
      Collecting meson-python==0.13.1
        Using cached meson_python-0.13.1-py3-none-any.whl.metadata (4.1 kB)
      Collecting meson==1.2.1
        Using cached meson-1.2.1-py3-none-any.whl.metadata (1.7 kB)
      Collecting wheel
        Using cached wheel-0.43.0-py3-none-any.whl.metadata (2.2 kB)
      Collecting Cython==3.0.5
        Using cached Cython-3.0.5-py2.py3-none-any.whl.metadata (3.2 kB)
      Collecting numpy>=2.0.0rc1
        Using cached numpy-2.0.0rc1.tar.gz (18.3 MB)
        Installing build dependencies: started
        Installing build dependencies: finished with status 'done'
        Getting requirements to build wheel: started
        Getting requirements to build wheel: finished with status 'done'
        Installing backend dependencies: started
        Installing backend dependencies: finished with status 'done'
        Preparing metadata (pyproject.toml): started
        Preparing metadata (pyproject.toml): finished with status 'error'
        error: subprocess-exited-with-error
      
        × Preparing metadata (pyproject.toml) did not run successfully.
        │ exit code: 1
        ╰─> [23 lines of output]
            + /Library/Frameworks/Python.framework/Versions/3.13/bin/python3.13 /private/var/folders/2v/8tn7gqqj4hb_d_4p_hchmk9m0000gn/T/pip-install-n2kuj6ja/numpy_453bc18c37eb422bb19b80324c3e9955/vendored-meson/meson/meson.py setup /private/var/folders/2v/8tn7gqqj4hb_d_4p_hchmk9m0000gn/T/pip-install-n2kuj6ja/numpy_453bc18c37eb422bb19b80324c3e9955 /private/var/folders/2v/8tn7gqqj4hb_d_4p_hchmk9m0000gn/T/pip-install-n2kuj6ja/numpy_453bc18c37eb422bb19b80324c3e9955/.mesonpy-dpfztv1f -Dbuildtype=release -Db_ndebug=if-release -Db_vscrt=md --native-file=/private/var/folders/2v/8tn7gqqj4hb_d_4p_hchmk9m0000gn/T/pip-install-n2kuj6ja/numpy_453bc18c37eb422bb19b80324c3e9955/.mesonpy-dpfztv1f/meson-python-native-file.ini
            The Meson build system
            Version: 1.2.99
            Source dir: /private/var/folders/2v/8tn7gqqj4hb_d_4p_hchmk9m0000gn/T/pip-install-n2kuj6ja/numpy_453bc18c37eb422bb19b80324c3e9955
            Build dir: /private/var/folders/2v/8tn7gqqj4hb_d_4p_hchmk9m0000gn/T/pip-install-n2kuj6ja/numpy_453bc18c37eb422bb19b80324c3e9955/.mesonpy-dpfztv1f
            Build type: native build
            Project name: NumPy
            Project version: 2.0.0rc1
            C compiler for the host machine: cc (clang 13.1.6 "Apple clang version 13.1.6 (clang-1316.0.21.2.5)")
            C linker for the host machine: cc ld64 764
            C++ compiler for the host machine: c++ (clang 13.1.6 "Apple clang version 13.1.6 (clang-1316.0.21.2.5)")
            C++ linker for the host machine: c++ ld64 764
            Cython compiler for the host machine: cython (cython 3.0.10)
            Host machine cpu family: aarch64
            Host machine cpu: aarch64
            Program python found: YES (/Library/Frameworks/Python.framework/Versions/3.13/bin/python3.13)
            Did not find pkg-config by name 'pkg-config'
            Found Pkg-config: NO
            Run-time dependency python found: NO (tried pkgconfig, pkgconfig and sysconfig)
      
            ../meson.build:41:12: ERROR: Python dependency not found
      
            A full log can be found at /private/var/folders/2v/8tn7gqqj4hb_d_4p_hchmk9m0000gn/T/pip-install-n2kuj6ja/numpy_453bc18c37eb422bb19b80324c3e9955/.mesonpy-dpfztv1f/meson-logs/meson-log.txt
            [end of output]
      
        note: This error originates from a subprocess, and is likely not a problem with pip.
      error: metadata-generation-failed
      
      × Encountered error while generating package metadata.
      ╰─> See above for output.
      
      note: This is an issue with the package mentioned above, not pip.
      hint: See above for details.
      [end of output]
  
  note: This error originates from a subprocess, and is likely not a problem with pip.
error: subprocess-exited-with-error

× pip subprocess to install build dependencies did not run successfully.
│ exit code: 1
╰─> See above for output.

note: This error originates from a subprocess, and is likely not a problem with pip.
Why I can't install packages successfully?Python is installed from python.org.
Can't be more appreciated if anyone can help.
