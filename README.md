# css-modal-styles
styles for modal window


.modal-backdrop {
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    background-color: #000;
    z-index: 1050;
    opacity: .2;
}

.modal {
    padding-right: 17px;
    display: block;
    overflow-x: hidden;
    overflow-y: auto;
    position: fixed;
    top: 0;
    left: 0;
    z-index: 1060;
    /* background-color: pink; */
    width: 100vw;
    height: 100vh;
}

.modal-dialog {
    width: 100%;
    max-width: 50rem;
    min-height: calc(100% - 3.5rem);
    margin: 1.75rem auto;
    /* background-color: red; */
    position: relative;
    /* left: 50%; */
    display: flex;
    align-items: center;
}

.modal-content {
    border-radius: 2rem;
    padding: 4rem;
    box-sizing: border-box;
    border-color: transparent;
    position: relative;
    display: flex;
    flex-direction: column;
    width: 100%;
    pointer-events: auto;
    background-color: #fff;
    background-clip: padding-box;
    border-radius: 1px solid rgba(0, 0, 0, .02);
    outline: none;
}
