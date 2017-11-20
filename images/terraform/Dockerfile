############################################################
# Dockerfile to build f5-super-netops enablement container
# Based on Alpine Linux, seasoned with tools and workflows
############################################################

# Start with an awesome, tiny Linux distro.
FROM f5devcentral/f5-super-netops-container:base

LABEL maintainer "h.patel@f5.com, n.pearce@f5.com"

# Set the SNOPS image name
ENV SNOPS_IMAGE terraform

# Copy in base FS from repo
COPY fs /


