# Limits Initializer

The limits Initializer is a [Kubernetes initializer](https://kubernetes.io/docs/admin/extensible-admission-controllers/#what-are-initializers) that injects resource limits to containers if limits are not set

## Usage

```
limits-initializer -h
```
```
Usage of limits-initializer:
  -annotation string
    	The annotation to trigger initialization (default "initializer.kubernetes.io/limits")
  -configmap string
    	The limits initializer configuration configmap (default "limits-initializer")
  -initializer-name string
    	The initializer name (default "limits.initializer.kubernetes.io")
  -namespace string
    	The configuration namespace (default "default")
  -require-annotation
    	Require annotation for initialization
```
