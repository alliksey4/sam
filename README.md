# SMILART APPLICATION MANAGER #

Options:

        -f  [archive.tar]       Docker load image from tar archive.

        -i  [image]:[version]   Install selected docker image.

        -u  [image]:[version]   Uninstall selected container to db.

        -x  [-f:-i:-u]          Debug mode from options.

        -I  [image]:[version]   Info to image.
	
        -c  [image]:[version]   Copy meta image in dirrectory /tmp.

        -l                      List installed image to db.

        -h                      Help

Environments:

        DOCKER_PATH             Path docker. default: DOCKER_PATH=/usr/bin/docker

        SAM_DB_LIST             Database from installed images. default: SAM_DB_LIST=/var/db/sam/list_installed

	BIN_DIR			Executable file is copied in dirrectory, default: BIN_DIR=/opt/bin
