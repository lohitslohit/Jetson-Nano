# Jetson-Nano


https://docs.docker.com/engine/install/ubuntu/




import logging
logging.basicConfig(filename='sampl.log', encoding='utf-8', level=logging.DEBUG)

logger=logging.getLogger(__name__)

try:
    1/0
except ZeroDivisionError as err:
    logger.error(err)
    logging.warning(err)
    logging.info(err)
    logging.debug(err) 
