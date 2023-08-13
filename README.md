# Grid-Garden-Solutions
- CSS Solution code to the Grid Garden game. Practice it here: [Grid Garden](https://cssgridgarden.com/).
- Make sure to give your best, and if you're stuck, you can refer to the solutions.

### Level 1
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-column-start: 3;
    }
    
### Level 2
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-column-start: 5;
    }
    
### Level 3
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-column-start: 1;
      grid-column-end: 4;
    }
    
### Level 4
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-column-start: 5;
      grid-column-end: 2;
    }
    
### Level 5
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-column-start: 1;
      grid-column-end: -2;
    }
    
### Level 6
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-column-start: -3;
    }
    
### Level 7
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-column-start: 2;
      grid-column-end: span 2;
    }
    
### Level 8
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-column-start: 1;
      grid-column-end: -1;
    }
    
### Level 9
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-column-start: span 3
      grid-column-end: 6;
    }
    
### Level 10
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-column: 4 / -1;
    }
    
### Level 11
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-column: 2 / span 3;
    }
    
### Level 12
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-row-start: 3;
    }
    
### Level 13
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-row: 3 / span 3;
    }
    
### Level 14
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-column: 2 / 3;
      grid-row: -1 / -2;
    }
    
### Level 15
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-column: 2 / span 4;
      grid-row: 1 / span 5;
    }
    
### Level 16
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-area: 1 / 2 / 4 / 6 ;
    }
    
### Level 17
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-area: 1 / 4 / 6 / 5;
    }

    #water-2 {
      grid-area: 2 / 3 / 5 / 6;
    }
    
### Level 18
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    .water {
      order: 0;
    }

    #poison {
      order: 1;
    }
    
### Level 19
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    .water {
      order: 0;
    }

    #poison {
      order: -1;
    }
    
### Level 20
    #garden {
      display: grid;
      grid-template-columns: 50% 50%;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-column: 1;
      grid-row: 1;
    }
    
### Level 21
    #garden {
      display: grid;
      grid-template-columns: repeat(8, 12.5%)
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-column: 1;
      grid-row: 1;
    }
    
### Level 22
    #garden {
      display: grid;
      grid-template-columns: 100px 3em 40% auto;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }
    
### Level 23
    #garden {
      display: grid;
      grid-template-columns: .17fr .83fr;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }
    
### Level 24
    #garden {
      display: grid;
      grid-template-columns: 50px repeat(3, 1fr) 50px;
      grid-template-rows: 20% 20% 20% 20% 20%;
    }

    #water {
      grid-area: 1 / 1 / 6 / 2;
    }

    #poison {
      grid-area: 1 / 5 / 6 / 6;
    }
    
### Level 25
    #garden {
      display: grid;
      grid-template-columns: 75px 0.6fr 0.4fr;
      grid-template-rows: 100%;
    }
    
### Level 26
    #garden {
      display: grid;
      grid-template-columns: 20% 20% 20% 20% 20%;
      grid-template-rows: repeat(4, 12.5px) 1fr;
    }

    #water {
      grid-column: 1 / 6;
      grid-row: 5 / 6;
    }
    
### Level 27
    #garden {
      display: grid;
      grid-template: 60% 40% / 200px 1fr;
    }

    #water {
      grid-column: 1;
      grid-row: 1;
    }
    
### Level 28
    #garden {
      display: grid;
      grid-template: 1fr 50px / 20% 1fr;
    }
