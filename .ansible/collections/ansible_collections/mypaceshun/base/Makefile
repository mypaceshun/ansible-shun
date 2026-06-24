PYTHON              = python3
VENV                = .venv

.PHONY: lint
lint: ${VENV}
	${VENV}/bin/ansible-lint

${VENV}:
	${PYTHON} -m venv --upgrade-deps ${VENV}
	${VENV}/bin/pip install ansible-lint yamllint
