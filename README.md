# Reddy1
this is for demo

adding some notes

namespace BaseLibrary.Repository
{
    public class ResponseBuilder : IResponseBuilder
    {

        private ILogger _logger;
        public ResponseBuilder(ILogger logger)
        {
            _logger = logger;
          
        }

        public string TEKCall()
        {
            _logger.DataBaseOperations();
            //TEK logic implement
            return "TEK Response";
        }
    }
}
