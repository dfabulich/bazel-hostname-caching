genrule(
	name='out',
	outs=['out.txt'],
	stamp=1,
	cmd='grep BUILD_HOST bazel-out/stable-status.txt > $@',
)
