# assets

<style>
  .grid-container {
    height: 150px;
    display: grid;
    grid-template-columns: repeat(20, 1fr);
    column-gap: 14px;
    width: 100%;
    overflow: hidden;
    background: transparent;
  }

  .grid-container .line {
    position: relative;
    width: 7px;
    height: 100%;
  }

  .grid-container .line::before,
  .grid-container .line::after {
    content: "";
    position: absolute;
    width: 100%;
    height: 7px;
    border-radius: 7px;
    background-color: #3b44d1;
    animation: upper-line 4s ease-in-out infinite alternate;
  }

  .grid-container .line::after {
    bottom: 0;
    background-color: #dc5245;
    height: calc(100% - 20px);
    animation: bottom-line 4s ease-in-out infinite alternate;
  }

  /* Delays */
  .grid-container .line:nth-child(1)::before, .grid-container .line:nth-child(1)::after { animation-delay: -0.1s; }
  .grid-container .line:nth-child(2)::before, .grid-container .line:nth-child(2)::after { animation-delay: -0.2s; }
  .grid-container .line:nth-child(3)::before, .grid-container .line:nth-child(3)::after { animation-delay: -0.3s; }
  .grid-container .line:nth-child(4)::before, .grid-container .line:nth-child(4)::after { animation-delay: -0.4s; }
  .grid-container .line:nth-child(5)::before, .grid-container .line:nth-child(5)::after { animation-delay: -0.5s; }
  .grid-container .line:nth-child(6)::before, .grid-container .line:nth-child(6)::after { animation-delay: -0.6s; }
  .grid-container .line:nth-child(7)::before, .grid-container .line:nth-child(7)::after { animation-delay: -0.7s; }
  .grid-container .line:nth-child(8)::before, .grid-container .line:nth-child(8)::after { animation-delay: -0.8s; }
  .grid-container .line:nth-child(9)::before, .grid-container .line:nth-child(9)::after { animation-delay: -0.9s; }
  .grid-container .line:nth-child(10)::before, .grid-container .line:nth-child(10)::after { animation-delay: -1s; }
  .grid-container .line:nth-child(11)::before, .grid-container .line:nth-child(11)::after { animation-delay: -1.1s; }
  .grid-container .line:nth-child(12)::before, .grid-container .line:nth-child(12)::after { animation-delay: -1.2s; }
  .grid-container .line:nth-child(13)::before, .grid-container .line:nth-child(13)::after { animation-delay: -1.3s; }
  .grid-container .line:nth-child(14)::before, .grid-container .line:nth-child(14)::after { animation-delay: -1.4s; }
  .grid-container .line:nth-child(15)::before, .grid-container .line:nth-child(15)::after { animation-delay: -1.5s; }
  .grid-container .line:nth-child(16)::before, .grid-container .line:nth-child(16)::after { animation-delay: -1.6s; }
  .grid-container .line:nth-child(17)::before, .grid-container .line:nth-child(17)::after { animation-delay: -1.7s; }
  .grid-container .line:nth-child(18)::before, .grid-container .line:nth-child(18)::after { animation-delay: -1.8s; }
  .grid-container .line:nth-child(19)::before, .grid-container .line:nth-child(19)::after { animation-delay: -1.9s; }
  .grid-container .line:nth-child(20)::before, .grid-container .line:nth-child(20)::after { animation-delay: -2s; }

  @keyframes upper-line {
    50% { height: calc(100% - 13px); }
    100% { background-color: #46f443; }
  }

  @keyframes bottom-line {
    50% { height: 7px; }
    100% { background-color: #5b38ee; }
  }
</style>

<div class="grid-container">
  <span class="line"></span>
  <span class="line"></span>
  <span class="line"></span>
  <span class="line"></span>
  <span class="line"></span>
  <span class="line"></span>
  <span class="line"></span>
  <span class="line"></span>
  <span class="line"></span>
  <span class="line"></span>
  <span class="line"></span>
  <span class="line"></span>
  <span class="line"></span>
  <span class="line"></span>
  <span class="line"></span>
  <span class="line"></span>
  <span class="line"></span>
  <span class="line"></span>
  <span class="line"></span>
  <span class="line"></span>
</div>
