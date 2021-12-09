window._genesys = {
  widgets: {
    webchat: {
      transport: {
        type: 'purecloud-v2-sockets',
        dataURL: 'https://api.mypurecloud.com.au',     // replace with API URL matching your region
        deploymentKey : '79f087ba-101e-4014-9311-51a82f4fbb96',  // replace with your Deployment ID
        orgGuid : '0cfd414c-cb21-4dc3-a6d4-baa951ee470c',              // replace with your Organization ID
        interactionData: {
          routing: {
            targetType: 'QUEUE',
            targetAddress: 'JD_CustomerService',
            priority: 2
          }
        }
      },
      userData: {
        addressStreet: '64472 Brown Street',
        addressCity: 'Lindgrenmouth',
        addressPostalCode: '50163-2735',
        addressState: 'FL',
        phoneNumber: '1-916-892-2045 x293',
        phoneType: 'Cell',
        customerId: '59606',
        // These fields should be provided via advanced configuration
        // firstName: 'Praenomen',
        // lastName: 'Gens',
        // email: 'praenomen.gens@calidumlitterae.com',
        // subject: 'Chat subject'
      }
    }
  }
};
