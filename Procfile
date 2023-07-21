web: erb nginx.conf.erb > nginx.conf && varify -buildpack-yml-path buildpack.yml nginx.conf "" "" && nginx -p $PWD -c ./nginx.conf
