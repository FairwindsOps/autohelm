<h1 id="autohelm">autohelm</h1>


<h2 id="autohelm.Response">Response</h2>

```python
Response(self, stdout, stderr, exitcode)
```

Utility class to simplify the results from call()

Positional Arguments:
- stdout(string)
- stderr (string)
- exitcode (sting,int)

Attributes:
- stdout
- stderr
- exitcode

Response() is truthy where Reponse.exitcode == 0
Response() is falsey where Reponse.exitcode != 0

<h2 id="autohelm.call">call</h2>

```python
call(args)
```

Wrapper utility function for subprocess.Popen.
Accepts list: `args`
Return tuple: `(stdout, stderr, exitcode)`

<h1 id="autohelm.chart">autohelm.chart</h1>


<h2 id="autohelm.chart.Chart">Chart</h2>

```python
Chart(self, chart)
```

<h1 id="autohelm.autohelm">autohelm.autohelm</h1>


<h2 id="autohelm.autohelm.AutoHelm">AutoHelm</h2>

```python
AutoHelm(self, file=None, dryrun=False, debug=False, helm_args=None, local_development=False)
```

Core AutoHelm class

Arguments:
- file(file object) - file object of the course.yml
- dryrun (bool) - passes --dry-run flag to helm binary
- debug (bool) - passes --debug flag to helm binar
- helm_args (list) - passes content of list as additional arguments to helm binary
- local_development (bool) - when true, most actions over the network are switched off

Attributes:
- stdout
- stderr
- exitcode

Response() is truthy where Reponse.exitcode == 0
Response() is falsey where Reponse.exitcode != 0

<h1 id="autohelm.cli">autohelm.cli</h1>


<h1 id="autohelm.config">autohelm.config</h1>


<h2 id="autohelm.config.Config">Config</h2>

```python
Config(self)
```

<h1 id="autohelm.meta">autohelm.meta</h1>


<h1 id="autohelm.helm">autohelm.helm</h1>


<h2 id="autohelm.helm.Helm">Helm</h2>

```python
Helm(self)
```

<h1 id="autohelm.course">autohelm.course</h1>


<h2 id="autohelm.course.Course">Course</h2>

```python
Course(self, file)
```

<h1 id="autohelm.exception">autohelm.exception</h1>


<h1 id="autohelm.repository">autohelm.repository</h1>


<h2 id="autohelm.repository.Repository">Repository</h2>

```python
Repository(self, repository)
```

