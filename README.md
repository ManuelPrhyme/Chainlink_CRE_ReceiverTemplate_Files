# Chainlink_CRE_ReceiverTemplate_Files

This repository contains all the essential files for implementing a **Chainlink CRE Consumer smart contract**.  

## Files Included
- **ReceiverTemplate.sol**  
  Abstract parent contract that defines the core receiver logic.  
  Must be inherited by consumer contracts to implement specific functionality.  

- **IERC165.sol**  
  Standard ERC-165 interface dependency (used for contract interface detection).  

- **IReceiver.sol**  
  Custom interface dependency for receiver functionality.  

- **Ownable**  
  Ownership control contract (should be imported from the [OpenZeppelin Contracts](https://github.com/OpenZeppelin/openzeppelin-contracts) repository).  

## Purpose
This template provides a structured starting point for building receiver contracts that integrate with Chainlink CRE.  
By inheriting from **ReceiverTemplate.sol**, developers can extend and customize consumer contracts while maintaining modularity, reusability, and adherence to established standards.
