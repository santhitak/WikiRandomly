<style>
  :global(.custom_btn) {
    text-transform: uppercase;
    appearance: button;
    background-color: rgb(34, 35, 39);
    background-image: none;
    border: 1px solid rgb(34, 35, 39);
    border-radius: 4px;
    box-shadow: #fff 4px 4px 0 0, rgb(34, 35, 39) 4px 4px 0 1px;
    box-sizing: border-box;
    color: #fff;
    cursor: pointer;
    display: inline-block;
    font-size: 14px;
    font-weight: 400;
    line-height: 20px;
    margin: 0 5px 10px 0;
    padding: .6rem 1rem;
    text-align: center;
    text-transform: none;
    touch-action: manipulation;
    user-select: none;
    -webkit-user-select: none;
    vertical-align: middle;
    white-space: nowrap;
  }

  :global(.custom_btn:focus) {
    text-decoration: none;
  }

  :global(.custom_btn:hover) {
    text-decoration: none;
  }

  :global(.custom_btn:active) {
    box-shadow: rgba(0, 0, 0, 0.125) 0 3px 5px inset;
    outline: 0;
  }

  :global(.custom_btn:not([disabled]):active) {
    box-shadow: #fff 2px 2px 0 0, rgb(34, 35, 39) 2px 2px 0 1px;
    transform: translate(2px, 2px);
  }
</style>
