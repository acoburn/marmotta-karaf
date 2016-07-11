# Marmotta Karaf Provisioning Feature

Provisioning features for Marmotta libraries in Karaf 4.x

    feature:repo-add mvn:org.apache.marmotta/marmotta-karaf/LATEST/xml/features

    feature:install ldpath
    feature:install ldpath-backend-file
    feature:install ldpath-backend-jena
    feature:install ldpath-backend-linkeddata
    feature:install ldpath-backend-sesame
    feature:install ldpath-template

    feature:install ldcache
    feature:install ldcache-backend-file
    feature:install ldcache-backend-infinispan

    feature:install ldclient
    feature:install ldclient-provider-facebook
    feature:install ldclient-provider-html
    feature:install ldclient-provider-ldap
    feature:install ldclient-provider-mediawiki
    feature:install ldclient-provider-phpbb
    feature:install ldclient-provider-rdf
    feature:install ldclient-provider-xml
    feature:install ldclient-provider-vimeo
    feature:install ldclient-provider-youtube

    feature:install marmotta-commons
