exports.Soder = {
  
  upStair: function( size, material ) {
    if( material == undefined ) {
      material = blocks.stairs.stone;
    }
    if( size > 50 ) {
      size = 50;
    }
    return box( material ).fwd().up().times( size );
  },
  
  downStair: function( size, material ) {
    if( material == undefined ) {
      material = blocks.stairs.stone;
    }
    if( size > 50 ) {
      size = 50;
    }
    return box( material ).fwd().down().times( size );
  },
  
  bridge: function( size, material ) {
    if( material == undefined ) {
      material = blocks.stone;
    }
    if( size > 50 ) {
      size = 50;
    }
    return box( material ).fwd().times( size );
  }
  
  
}
