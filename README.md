# add-function-reset-draft-6
function resetMyGarage() external override {
        delete garages[msg.sender];
    }
